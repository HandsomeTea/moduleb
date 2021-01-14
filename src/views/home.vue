<template>
    <el-main class="demo_style">
        moduleb language test: {{ $t('SUCCESS') }}
        <p>主服务没3秒切换一次语言以触发测试</p>
    </el-main>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator';
@Component
export default class Hoom extends Vue {

}
</script>
