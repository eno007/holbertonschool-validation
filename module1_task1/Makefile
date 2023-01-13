build: ## building hugo
	hugo

clean: ## removing dist
	rm -r ./dist/

post: ## creates new post
	hugo new posts/$(POST_NAME).md
	sed -i '/title:/c\title: "$(POST_TITLE)"' content/posts/$(POST_NAME).md