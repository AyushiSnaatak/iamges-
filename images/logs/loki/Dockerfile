ARG IMAGE_NAME=loki
ARG IMAGE_TAG=3

FROM dhi.io/${IMAGE_NAME}:${IMAGE_TAG}
ARG IMAGE_NAME
ARG IMAGE_TAG
LABEL source.image="dhi.io/${IMAGE_NAME}:${IMAGE_TAG}" \
      source.registry="dhi.io" \
      source.tag="${IMAGE_TAG}" \
      source.name="${IMAGE_NAME}" \
      description="Hardened ${IMAGE_NAME} image from Docker Hardened Images"
