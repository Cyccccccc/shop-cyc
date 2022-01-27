<template>
  <div>
    <Header></Header>
    <router-view></router-view>
    <TypeNav></TypeNav>
    <ListContainer></ListContainer>
    <TodayRecommend></TodayRecommend>
    <Rank></Rank>
    <Like></Like>
    <Floor></Floor>

    <Footer v-show="!$route.meta.isHideFooter" ></Footer>
  </div>
</template>

<script>
import Header from "@/components/Header"
import Footer from "@/components/Footer"
import Brand from '@/components/Brand'
import Floor from '@/components/Floor'
import Like from '@/components/Like'
import ListContainer from '@/components/ListContainer'
import Rank from '@/components/Rank'
import TodayRecommend from '@/components/TodayRecommend'
import TypeNav from '@/components/TypeNav'


export default {
  name: '',
  components:{
    Header,
    Footer,
    Brand,
    Floor,
    Like,
    ListContainer,
    Rank,
    TodayRecommend,
    TypeNav
  }
}
</script>

<style lang="less" scoped>

</style>
