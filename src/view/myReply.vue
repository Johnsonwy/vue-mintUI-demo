<!--我的讨论-回复-->
<template>
  <div class="system">
    <nav class="tabtop">
      <ul class="dbox">
        <li class="flex tab">发表<span>1</span></li>
        <li class="flex tab active">回复<span>10</span></li>
      </ul>
    </nav>
    <div class="cm-main">
      <ul class="discuss-list">           
        <li>              
          <a href="javascript:;" class="block">
            <h3 class="elli">创新坦克对战手游《坦克大战OL》5月25日二测开启</h3>
          </a>
          <section class="dbox">                
            <p class="flex"><span class="elli max">哈哈还差哈哈还差哈哈还差哈哈还差</span></p>
            <p class="flex"><em>2016-07-19 19:42</em></p>
          </section>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>

export default {
  name: 'new',
  components: {

  },
  data () {
    return {
      load:true,
      moreTip:'正在加载',
      loadshow: false,
      loadtext: '加载中',
    }
  },
  created () {
    let that = this;
  },
  mounted(){
    //document.querySelector('.edit').style.height = document.documentElement.clientHeight+'px';
  },
  methods: {
    
  },
}
</script>


<style scoped lang="less" type="text/less" rel="stylesheet/less">
  .icos{
    //background: url(../assets/img/per-in.png) 0 0 no-repeat;
  }
  .tabtop{
    position: fixed;
    width: 6.4rem;
    left: 50%;
    margin-left: -3.2rem;
    right: 0;
    top: 0;
    z-index: 99;
    overflow: hidden;
    box-sizing: border-box;
    height: .82rem;
    line-height: .81rem;
    background-color: rgba(255,255,255,1);
    text-align: center;
    font-size: .3rem;
    color: #353535;
    .active{
      border-bottom-color: #f48400;
      color: #f48400;
    }
    li{
      border-bottom: 1px solid rgb(232,232,232);
    }
  }
  .cm-main{
    padding-top:.82rem;
  }
  .discuss-list{
    padding:0 .3rem;
    li{
      padding: .2rem 0;
      font-size: .26rem;
      line-height: 1;
      border-bottom: 1px solid #e8e8e8;
      a{
        display: block;
        color: #333;
      }
      h3{
        font-size: .32rem;
        line-height: .52rem;
        padding-bottom: .10rem;
      }
      .flex:last-child{
        text-align: right;
      }
      .dbox{
        color: #a0a0a0;
        font-size: .26rem;
      }
      .icos{
        margin-right: .30rem;
        color: #a0a0a0;
        font-size: .24rem;       
        i{
          display: inline-block;
          margin-right: .04rem;
          width: .29rem;
          height: .26rem;
          background: url(../assets/img/dis-1.png) no-repeat;
          background-size: 100%;
          vertical-align: -.03rem;
        }
      }
      .ico2 i{
        background-image: url(../assets/img/dis-2.png);
      }
      .max{
        display: inline-block;
        max-width: 3.3rem;
      }
    }
  }
  
</style>
