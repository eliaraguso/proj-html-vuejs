<template>
    <footer>
        <div id="footer-top"></div>
        <div id="footer-bottom">
            <p>© Copyright 2012 - 2021 | Avada Theme by <a href="#">ThemeFusion</a> | All Rights Reserved | Powered by <a href="#">WordPress</a></p>
        </div>
    </footer>
</template>


<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
    #footer-bottom {
        font-size: 14px;
        font-weight: 300;
        line-height: 31.5px;
        padding: 24px 80px;
        background-color: #f7f7f7;
        color: #7e8890;
        a {
            color: #2b2b2b;
            text-decoration: none;
            &:hover {
                color: #3bafbf;
            }
        }
    }
</style>