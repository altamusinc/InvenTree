Build the image

docker build . --target production --tag wdueease/inventree -f contrib/container/Dockerfile

Push the image

docker push wdueease/inventree