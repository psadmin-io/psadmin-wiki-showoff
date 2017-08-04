!SLIDE center subsection

# Add Your Article

!SLIDE bullets

# Add a page

1. `touch posts/pca/hiera_hashes.md`
1. Add the front-matter
1. Write your post
1. Add your article link to `_data\pca.yml`

!SLIDE

# Configure Article

## front-matter

    @@@ yaml
    ---
    title: Sample psft_customizations.yaml
    layout: en
    permalink: /posts/pca/sample_yaml/
    ---

## _data/pca.yml

    @@@ yaml
    Sample psft_customizations.yaml:  "/posts/pca/sample_yaml/"
    DPK Cleanup Process:              "/posts/pca/cleanup/"