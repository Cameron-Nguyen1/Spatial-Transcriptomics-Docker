# Spatial-Transcriptomics-Docker
Docker container for conducting spatial transcriptomics output, tested on 10x's Spaceranger.
You'll have to provide your own github token to build the image.

--- Example run script below ---

bash:
  docker run \
   -v /mnt/d/Spatial_A1_D1:/usr/local/work/ \
   -it spatial --slides "A1,D1" --outputdir MyDir
