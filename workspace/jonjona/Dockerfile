# Copyright 2016 Daniel Nüst
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#   http://www.apache.org/licenses/LICENSE-2.0
FROM nuest/docker-qgis-model:trusty
MAINTAINER Daniel Nüst <daniel.nuest@uni-muenster.de>

COPY . /workspace

# Execute the following commands _in the directory of this file_ to build and execute a self-contained image:
# BUILD COMMAND: docker build -t qgis-model-jonjona .
# RUN COMMAND: docker run --name jonjona -it qgis-model-jonjona
# Extract results: docker cp jonjona:/workspace results
# RUN with random centroids:
#   docker run --name jonjona-random qgis-model-jonjona -e "QGIS_KMEANS_RANDOM_CENTROIDS=true"
#   docker cp jonjona-random:/workspace results/random 