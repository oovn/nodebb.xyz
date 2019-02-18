# get source
rm -rf NodeBB
curl -L https://github.com/NodeBB/NodeBB/tarball/master | tar xz && mv NodeBB* NodeBB
# make redis db > info db
# edit db config.json
# git push
# make nodejs > github url
# Deploy only > NPM_RUN = dev
# Add storage pvc > /opt/app-root/src/NodeBB/public
