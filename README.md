# VulkanLearning

![GitHub Repo stars](https://img.shields.io/github/stars/CMDR-Piboy314/VulkanLearning?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/CMDR-Piboy314/VulkanLearning?style=social)

![GitHub top language](https://img.shields.io/github/languages/top/CMDR-Piboy314/VulkanLearning)
![Lines of code](https://img.shields.io/tokei/lines/github/CMDR-Piboy314/VulkanLearning)
![GitHub repo size](https://img.shields.io/github/repo-size/CMDR-Piboy314/VulkanLearning)

![GitHub issues](https://img.shields.io/github/issues/CMDR-Piboy314/VulkanLearning)
![GitHub pull requests](https://img.shields.io/github/issues-pr/CMDR-Piboy314/VulkanLearning)
![GitHub](https://img.shields.io/github/license/CMDR-Piboy314/VulkanLearning)

![GitHub release (latest by date)](https://img.shields.io/github/v/release/CMDR-Piboy314/VulkanLearning)
![GitHub all releases](https://img.shields.io/github/downloads/CMDR-Piboy314/VulkanLearning/total)

The CMakeLists.txt is made for macOS on aarch64 with some environment variables, this is the section of my ~/.bash_profile for vulkan. This is very easily converted to Linux, and for Windows users a surf on the interwebs for vulkan CMakeLists.txt or vulkan Makefile should get you up and running easily.
```
# Vulkan environment variables
export VULKAN_ROOT_LOCATION="$HOME/"
export VULKAN_SDK_VERSION="1.3.204.1"
export VULKAN_SDK="$VULKAN_ROOT_LOCATION/VulkanSDK/$VULKAN_SDK_VERSION/macOS/"
export VK_ICD_FILENAMES="$VULKAN_SDK/etc/vulkan/icd.d/MoltenVK_icd.json"
export VK_LAYER_PATH="$VULKAN_SDK/etc/vulkan/explicit_layers.d"
export PATH="$VULKAN_SDK/bin:$PATH"
```
