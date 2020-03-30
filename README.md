# 13903-Regentview-Ave-Bellflower-CA-90706
# Step 1: Authenticate
$ cat ~/GH_TOKEN.txt | docker login docker.pkg.github.com -u BitCashCF --password-stdin

# Step 2: Tag
$ docker tag IMAGE_IDdocker.pkg.github.com/bitcashcf/repository-name/IMAGE_NAME:VERSION

# Step 3: Publish
$ docker push docker.pkg.github.com/bitcashcf/repository-name/IMAGE_NAME:VERSION

