# First website update

The first website update that we will do is add some headshots to the website. 

Notes:

- All headshots should be cropped to be 1:1 aspect ratio with the head centered

# Starting with the path-cc.io website

## Setting up the repo

Go to the repo and copy the code url and create a fork.

```shell
git clone https://github.com/path-cc/path-cc.github.io.git

# Move to that directory

git remote add upstream https://github.com/path-cc/path-cc.github.io.git
git remote set-url origin <the fork url>
```

## Creating a new branch

```shell
# Create a new branch to make changes on 
git checkout -b update-team
```

## Update the team

Run the website with the README.

Add a file name <first>-<last>.yaml to the `_data/team/*`
Add picture with same naming scheme to `images/team/*`

