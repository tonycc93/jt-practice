<template>
    <div id="redItemMenu">
        <ul class="menu">
            <li><a href="">首页</a></li>
            <li><a href="">博客</a>
                <ul class="drop-menu">
                    <li><a href="">CSS3</a></li>
                    <li><a href="">SASS</a></li>
                    <li><a href="">JavaScript</a></li>
                    <li><a href="">jQuery</a></li>
                </ul>
            </li>
            <li><a href="">案例</a></li>
            <li><a href="">资源</a></li>
            <li><a href="">前端收藏夹</a></li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: 'redItemMenu',
        data(){

        }
    }
</script>

<style lang="scss" scoped>
    $color: #fff !default; //设置文本颜色
    $bgColor: #34495e !default; //设置背景色
    $sfbgColor: #e74c3c !default; //设置悬浮背景色
    $fontSize: 14px !default; //设置字号
    $fontFamily: Arial, Helvetica !default; //设置字体
    $width: 462px !default; //设置默认宽

    %clearfix {
        & {
            *zoom: 1;
        }

        &:before, &:after {
            content: "";
            display: table;
        }

        &:after {
            clear: both;
            overflow: hidden;
        }
    }

    %listStyle {
        margin: 0;
        padding: 0;
        list-style: none outside none;
    }

    .menu {
        li {

        }
    }
</style>