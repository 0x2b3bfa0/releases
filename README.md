# Example of a GitHub-native approach to releases

With GitHub Releases, tags are created automatically each time a release is published and **before** the GitHub Actions `release` event is triggered.

## Creating a new release
![](https://github.com/0x2b3bfa0/releases/raw/main/1.png)
![](https://github.com/0x2b3bfa0/releases/raw/main/2.png)
![](https://github.com/0x2b3bfa0/releases/raw/main/3.png)

## Viewing the triggered workflow
https://github.com/0x2b3bfa0/releases/actions/workflows/release.yml

## Underlying release event

https://github.com/0x2b3bfa0/releases/blob/24843b98a2129ee170733347f7da8f8e8230c7cd/.github/workflows/release.yml#L2-L3
https://github.com/0x2b3bfa0/releases/blob/24843b98a2129ee170733347f7da8f8e8230c7cd/.github/workflows/release.yml#L9
