.PHONY: generate-collector-components
generate-collector-components: 
	cd gen_edot_col_components && pip install -r requirements.txt && python3 render_md.py

.PHONY: check-md-gen
check-md-gen: 
	cd gen_edot_col_components && pip install -r requirements.txt && python3 check_md.py

.PHONY: install
install:
	bundle install

.PHONY: build-site
build-site:
	bundle exec jekyll build

.PHONY: check-links
check-links: build-site
	bundle exec htmlproofer --assume_extension '.html' --swap-urls '^/opentelemetry/:/' --ignore_urls '/http:\/\/localhost:4000.*/','/https:\/\/elastic.github.io\/opentelemetry\/*/' --no_enforce_https ./_site

.PHONY: run-local
run-local: generate-collector-components
	bundle exec jekyll serve
