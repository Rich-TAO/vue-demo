<template>
    <div class="search">
        <search placeholder="请输入酒名、商品、用户等"></search>
    </div>
</template>

<script>
import { Search } from 'vux'
export default {
    name:'Search',
    components: {
        'search':Search
    }
}
</script>

<style lang="less" scoped>
ul{
                width: 100%;
                display: flex;
                justify-content: space-between;
                padding: 0 30px;
                li{
                    width: 334px;
                    img{
                        width: 334px;
                        height: 220px;
                    }
                    .p1{
                        font-size: 24px;
                        color: #000;
                        font-family: PingFang SC;
                    }
                    .p2{
                        font-size: 34px;
                        color: #8D0F10;
                        font-family: DIN;
                        span{
                            font-size: 24px;
                        }
                    }
                    .p3{
                        font-size: 24px;
                        color: #666;
                        display: flex;
                        justify-content: space-between;
                        align-items: center;
                        .p3-left{
                            text-decoration: line-through;
                        }
                    }
                }
            }
</style>


