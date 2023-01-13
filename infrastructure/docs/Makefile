all:
	@which mandoc > /dev/null || sudo apt install mandoc
	@mkdir -p html
	@rm -f html/*.html
	@for manpage in man/*; do \
		manname="$$(basename "$$manpage")"; \
		echo "===> Processing $${manname}"; \
		mandoc -Thtml -O man="%N.%S.html",toc,style="style.css" "$${manpage}" > "html/$${manname}.html"; \
	 done
	@cd html
	@ln -s swirlbuild.7.html html/index.html
