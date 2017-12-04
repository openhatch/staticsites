all: index.html hackathon/index.html learning/index.html about/index.html old-index/index.html

clean:
	@rm index.html
	@rm hackathon/index.html

index.html: template.php page-data/index
	php page-data/index > index.html

old-index/index.html: template.php page-data/old-index
	php page-data/old-index > old-index/index.html

hackathon/index.html: template.php page-data/hackathon
	php page-data/hackathon > hackathon/index.html

learning/index.html: template.php page-data/learning
	php page-data/learning > learning/index.html

about/index.html: template.php page-data/about
	php page-data/about > about/index.html
