# Minimal makefile for Sphinx documentation
#

# You can set these variables from the command line.
SPHINXOPTS    =
SPHINXBUILD   = sphinx-build
SPHINXPROJ    = {{cookiecutter.repository_name}}
SOURCEDIR     = .
BUILDDIR      = _build

# Put it first so that "make" without argument is like "make help".
help:
	@$(SPHINXBUILD) -M help "$(SOURCEDIR)" "$(BUILDDIR)" $(SPHINXOPTS) $(O)

.PHONY: help Makefile

# Catch-all target: route all unknown targets to Sphinx using the new
# "make mode" option.  $(O) is meant as a shortcut for $(SPHINXOPTS).
%: Makefile
	@$(SPHINXBUILD) -M $@ "$(SOURCEDIR)" "$(BUILDDIR)" $(SPHINXOPTS) $(O)
	@if [ $@ = "html" ]; then \
    	rm -rf ../docs; \
    	cp -r _build/html ../docs; \
    	touch ../docs/.nojekyll; \
    	rm -rf _build; \
    else \
    	rm -rf ../{{cookiecutter.repository_name}}.pdf; \
    	mv _build/latex/{{cookiecutter.repository_name}}.pdf ../{{cookiecutter.repository_name}}.pdf; \
    	rm -rf _build; \
    fi
