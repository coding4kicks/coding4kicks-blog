Personal website using hexo.

Clean - Build - Serve:
hexo clean; hexo generate; hexo serve

Deploy:
aws s3 sync ./public s3://www.coding4kicks.com; aws s3 sync ./public s3://coding4kicks.com;
