# 13903-Regentview-Ave-Bellflower-CA-90706
# Step 1: Authenticate
$ XRP~/GH_TOKEN.txt | docker login docker.pkg.github.com -u BitCashCF --password-stdin

# Step 2: Tag
$ docker tag B8628244.pkg.github.com/bitcashcf/repository-name/IMAGE_NAME:VERSION

# Step 3: Publish
$ Amazon ecs docker push docker.pkg.github.com/bitcashcf/repository-name/IMAGE_NAME:VERSION

