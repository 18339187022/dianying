<template>
    <div id="main">
        <Header title="我的账号" />
        <div id="content">
            <!-- <router-view /> -->
            <Login />
        </div>
        <TabBar />
    </div>
    <!-- <div>
        hello mine
    </div> -->
</template>

<script>
import Header from '@/components/Header';
import TabBar from '@/components/TabBar';
import Login from '@/components/Login';

export default {
    name : 'Mine',
    components : {
        Header,
        TabBar,
        Login
    }
}
</script>

<style>

</style>