# Feat
- youtube/add support version `v18.19.36` & `v18.31.40`
- youtube/litho-filter: update filter
- youtube/shared-resource-id If the target resource ID is not found, empty index is returned instead of generating patch exception
- youtube/translations: update translation Chinese Traditional, Indonesian, Russian, Ukrainian, Vietnamese

# Fixed
- youtube/custom-playback-speed: does not work on tablet devices
- youtube/custom-playback-speed: when user opens the sharing panel, the custom playback speed panel opens
- youtube/default-video-quality: rollback commit
- youtube/hide-layout-components: custom filters are separated by commas instead of line-by-line
- youtube/hide-layout-components: expandable chip under videos not hidden in related videos
- youtube/litho-filter: don't remove the buffer until the thread stops
- youtube/old-quality-layout: does not work on tablet devices
- youtube/overlay-button: overlay button not hidden when scrubbing seekbar
- youtube/overlay-button: trim empty space from package name
- youtube/settings: remove disable some settings code for tablet devices
