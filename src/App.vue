<template>
  <MlCadViewer
    locale="en"
    url="https://cdn.jsdelivr.net/gh/mlight-lee/cad-data/data/anteen.dwg"
  />
</template>

<script setup lang="ts">
import { AcApSettingManager } from '@mlightcad/cad-simple-viewer'
import { MlCadViewer } from '@mlightcad/cad-viewer'

AcApSettingManager.instance.isShowCommandLine = false
// Decide whether to show vertical toolbar at the right side, performance stats, coordinates in status bar, etc.
// AcApSettingManager.instance.isShowToolbar = false
// AcApSettingManager.instance.isShowStats = false
// AcApSettingManager.instance.isShowCoordinate = false
</script>

