<template>
<div class="wrap">
    <div class="hdr">
        <div class="w">
            <a class="logo" rel="nofollow" href="https://muli.tv">牡蛎tv</a>
            <h1 class="hidden">牡蛎tv,软件</h1>
            <form name="search" id="search" class="hidden-xs hidden-sm" action="https://muli.tv/pc-fe-api/search" method="get"></form>
            <div id="rank">
                <ul>
                    <li>
                        <a href="/rank">
                            <i class="fas fas-list-ol"></i>
                            <span>排行榜</span>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
    <div class="nav">
        <div class="w">
            <div class="nav-inner clearfix">
                <ul class="clearfix" style="float:left">
                    <li class="active">
                        <a href="https://muli.tv" rel="nofollow">所有</a>
                    </li>
                    <li class="hidden-xs">
                        <a href="/c/app">App类</a>
                    </li>
                    <li class="hidden-xs">
                        <a href="/c/manage">管理类</a>
                    </li>
                </ul>
                <a rel="noreferrer noopener" target="_blank" href="https://muli.tv/user/message/2" class="feedback">反馈</a>
            </div>
        </div>
    </div>
    <div class="bdy">
        <div class="main no-size" id="page">
            <div class="inner">
                <div class="item muli-mall">
                    <div class="item-inner">
                        <div class="item-hd">
                            <a target="_blank" href="/mall" class="item-icon">
                                <img src="../assets/icon/twotone-store_mall_directory-24px.svg" width="48" height="48" alt="mall"/>
                            </a>
                        </div>
                        <div class="item-bd"></div>
                        <div class="item-ft"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>
<script>
export default {
  name: 'Index',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
