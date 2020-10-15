<template>
<div>
    <el-container class="container">
        <Aside/>
        <el-container class="sub-container">
            <Header/>
            <Page/>
        </el-container>
    </el-container>
</div>
</template>

<style lang="scss">
.container {
    height: 100vh;
}
.sub-container {
    flex-direction: column;
}
</style>

<script>
import Header from './header'
import Page from './page'
import Aside from './aside'

export default {
    name: 'Main',
    components: {
        Header,
        Page,
        Aside
    }
}
</script>
