# Upload Script
``` bash
$ aws s3 sync . s3://slate.khou22.com --exclude ".git/*" --exclude "*/.DS_Store" --exclude "README.md"
```

# Test the syncing without actually performing action
``` bash
$ aws s3 sync . s3://slate.khou22.com --exclude ".git/*" --exclude "*/.DS_Store" --exclude "README.md" --dryrun
```

# AWS CLI Sync Docs
http://docs.aws.amazon.com/cli/latest/reference/s3/sync.html

# Configuration
http://docs.aws.amazon.com/AmazonS3/latest/user-guide/static-website-hosting.html

# Bugs
1. Mobile optimizations for "About" section overlapping with screenshot
