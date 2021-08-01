# List files:
gsutil cp gs://arxiv-dataset/arxiv/

# Download pdfs from March 2020:
gsutil cp gs://arxiv-dataset/arxiv/arxiv/pdf/2003 / ./a_local_directory/

# Download all the source files
gsutil cp -r -n gs://arxiv-dataset/arxiv/ D:\arxiv
