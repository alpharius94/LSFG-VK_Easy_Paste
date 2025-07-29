> [!NOTE]
> 스팀덱 유저가 lsfg-vk 및 플러그인등을 쉽게 설치하기 위한 페이지입니다.   
> This page for just help to easy installation lsfg-vk for Steamdeck User.   
> **WIP.**

> [!WARNING]
> 버전 0.9.0 부터는 더이상 user-wide installation 을 지원하지 않습니다.   
> As of version 0.9.0, user-wide installations are not supported anymore!   
> 과거 버전을 설치했다면 다음 파일들을 삭제해주세요.   
> If you installed an older version of lsfg-vk, delete these files before proceding:   
> ```
> ~/.local/lib/liblsfg-vk.so
> ```   
> ```
> ~/.local/share/vulkan/implicit_layer.d/VkLayer_LS_frame_generation.json
> ```
---
# LSFG
## LSFG-VK Download and Install
#### 다운로드 페이지<br />LSFG-VK Release Page
> <https://github.com/PancakeTAS/lsfg-vk/releases>
<br />

**.zst 파일 설치 for 스팀덱 유저<br />.zst FILE for Steamdeck User**
> ```
> sudo pacman -U ./lsfg-vk-XXX.tar.zst
> ```

**ZIP파일로 다운로드한 경우**
**if you downloaded the generic .zip file:**
**(keep track of where it unzips to for uninstalling!)**
> ```
> cd /usr/local
> ```
> ```
> unzip /path/to/lsfg-vk-XXX.zip
> ```


# 덱키 로더<br />Decky Loader
## 다운로드 및 설치 스크립트<br />Download and Install Script
```
curl -L https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/install_release.sh | sh
```
## 제거 스크립트<br />Uninstall Script
```
curl -L https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/uninstall.sh | sh
```
# 덱키 로더 LSFV-VK 플러그인<br />Decky Loader
## 다운로드 및 설치 스크립트<br />Download and Install Script
```
https://github.com/xXJSONDeruloXx/decky-lossless-scaling-vk/releases
```
