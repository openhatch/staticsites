all: index.html schedule/index.html about/index.html old-index/index.html

clean:
	@rm index.html
	@rm hackathon/index.html

index.html: template.php page-data/index
	php page-data/index > index.html

old-index/index.html: template.php page-data/old-index
	php page-data/old-index > old-index/index.html

schedule/index.html: template.php page-data/schedule
	php page-data/schedule > schedule/index.html

about/index.html: template.php page-data/about
	php page-data/about > about/index.html
