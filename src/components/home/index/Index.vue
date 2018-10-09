<template>
  <div id="app">
    <headerWrapper :style="{height:screenHeight+'px'}" :headerBackgroundImage="headerImage"></headerWrapper>
    <article class="article">
      <div class="article-head">
        <main>
          <carousel></carousel>
        </main>
        <div class="sidebar">
          <div class="toppic">
            <li v-for="at in articles">
              <a :href="at.href" :title="at.title" target="_blank">
                <i><img :src="at.img"></i>
                <h2>{{at.title}}</h2>
                <span>{{at.tag}}</span>
              </a>
            </li>
          </div>
        </div>
      </div>
      <div class="blogs" data-scroll-reveal="enter bottom over 1s" data-scroll-reveal-id="1"
           data-scroll-reveal-initialized="true">
        <h3 class="blogtitle"><a href="#" target="_blank">作为一个设计师,如果遭到质疑你是否能恪守自己的原则</a></h3>
        <span class="blogpic"><a href="#" title="作为一个设计师,如果遭到质疑你是否能恪守自己的原则"><img
          src="static/img/3.jpg"
          alt="作为一个设计师,如果遭到质疑你是否能恪守自己的原则"></a></span>

        <p class="blogtext">曾经有站长找我求助，他说他不知道该怎么办，自己做出来的网站，不仅没有得到大家的认可，反而让大家给他开了一个评判大会。他自己认为已经是做的最好的，却遭受大家无情的... </p>
        <div class="label-tag">
          <ul>
            <li class="timer"><i class="el-icon-biaoqian"> GoLang </i></li>
            <li class="timer"><i class="el-icon-biaoqian"> PHP </i></li>
            <li class="timer"><i class="el-icon-biaoqian"> JavaScript </i></li>
          </ul>
        </div>
        <div class="bloginfo">
          <ul>
            <li class="timer"><i class="el-icon-yonghu1"> Sammy</i></li>
            <li class="timer"><i class="el-icon-shijian"> 2018-10-08</i></li>
            <li class="view"><i class="el-icon-yanjing"><span> 2</span>已阅读</i></li>
          </ul>
        </div>
      </div>
      <div class="blogs" data-scroll-reveal="enter bottom over 1s" data-scroll-reveal-id="1"
           data-scroll-reveal-initialized="true">
        <h3 class="blogtitle"><a href="#" target="_blank">作为一个设计师,如果遭到质疑你是否能恪守自己的原则</a></h3>
        <span class="blogpic"><a href="#" title="作为一个设计师,如果遭到质疑你是否能恪守自己的原则"><img
          src="static/img/3.jpg"
          alt="作为一个设计师,如果遭到质疑你是否能恪守自己的原则"></a></span>

        <p class="blogtext">曾经有站长找我求助，他说他不知道该怎么办，自己做出来的网站，不仅没有得到大家的认可，反而让大家给他开了一个评判大会。他自己认为已经是做的最好的，却遭受大家无情的... </p>
        <div class="label-tag">
          <ul>
            <li class="timer"><i class="el-icon-biaoqian"> GoLang </i></li>
            <li class="timer"><i class="el-icon-biaoqian"> PHP </i></li>
            <li class="timer"><i class="el-icon-biaoqian"> JavaScript </i></li>
          </ul>
        </div>
        <div class="bloginfo">
          <ul>
            <li class="timer"><i class="el-icon-yonghu1"> Sammy</i></li>
            <li class="timer"><i class="el-icon-shijian"> 2018-10-08</i></li>
            <li class="view"><i class="el-icon-yanjing"><span> 2</span>已阅读</i></li>
          </ul>
        </div>
      </div>
      <div class="blogs" data-scroll-reveal="enter bottom over 1s" data-scroll-reveal-id="1"
           data-scroll-reveal-initialized="true">
        <h3 class="blogtitle"><a href="#" target="_blank">作为一个设计师,如果遭到质疑你是否能恪守自己的原则</a></h3>
        <span class="blogpic"><a href="#" title="作为一个设计师,如果遭到质疑你是否能恪守自己的原则"></a></span>

        <p class="blogtext">曾经有站长找我求助，他说他不知道该怎么办，自己做出来的网站，不仅没有得到大家的认可，反而让大家给他开了一个评判大会。他自己认为已经是做的最好的，却遭受大家无情的... </p>
        <div class="label-tag">
          <ul>
            <li class="timer"><i class="el-icon-biaoqian"> GoLang </i></li>
            <li class="timer"><i class="el-icon-biaoqian"> PHP </i></li>
            <li class="timer"><i class="el-icon-biaoqian"> JavaScript </i></li>
          </ul>
        </div>
        <div class="bloginfo">
          <ul>
            <li class="timer"><i class="el-icon-yonghu1"> Sammy</i></li>
            <li class="timer"><i class="el-icon-shijian"> 2018-10-08</i></li>
            <li class="view"><i class="el-icon-yanjing"><span> 2</span>已阅读</i></li>
          </ul>
        </div>
      </div>
      <div class="blogs" data-scroll-reveal="enter bottom over 1s" data-scroll-reveal-id="1"
           data-scroll-reveal-initialized="true">
        <h3 class="blogtitle"><a href="#" target="_blank">作为一个设计师,如果遭到质疑你是否能恪守自己的原则</a></h3>
        <span class="blogpic"><a href="#" title="作为一个设计师,如果遭到质疑你是否能恪守自己的原则"><img
          src="static/img/3.jpg"
          alt="作为一个设计师,如果遭到质疑你是否能恪守自己的原则"></a></span>

        <p class="blogtext">曾经有站长找我求助，他说他不知道该怎么办，自己做出来的网站，不仅没有得到大家的认可，反而让大家给他开了一个评判大会。他自己认为已经是做的最好的，却遭受大家无情的... </p>
        <div class="label-tag">
          <ul>
            <li class="timer"><i class="el-icon-biaoqian"> GoLang </i></li>
            <li class="timer"><i class="el-icon-biaoqian"> PHP </i></li>
            <li class="timer"><i class="el-icon-biaoqian"> JavaScript </i></li>
          </ul>
        </div>
        <div class="bloginfo">
          <ul>
            <li class="timer"><i class="el-icon-yonghu1"> Sammy</i></li>
            <li class="timer"><i class="el-icon-shijian"> 2018-10-08</i></li>
            <li class="view"><i class="el-icon-yanjing"><span> 2</span>已阅读</i></li>
          </ul>
        </div>
      </div>
    </article>
    <foote></foote>
  </div>
</template>

<script>
  import headerWrapper from '@/components/home/layouts/header'
  import carousel from '@/components/home/layouts/carousel'
  import foote from '@/components/home/layouts/footer'

  export default {
    name: 'Index',
    components: {headerWrapper, carousel,foote},
    data: function () {
      return {
        screenHeight: (window.innerHeight),
        scrollTop: 0,
        scrollStatus: true,
        headerImage: "/static/img/40.jpg",
        articles: [
          {
            href: "#1",
            title: "安静地做一个爱设计的女子",
            tag: "慢生活",
            img: "/static/img/1.jpg"
          },
          {
            href: "#2",
            title: "个人博客，属于我的小世界！",
            tag: "目录1",
            img: "/static/img/2.jpg"
          },
        ],
      }
    },
    mounted() {
      const that = this;
      window.onresize = function () {
        that.screenHeight = (window.innerHeight);
      };
      document.onscroll = function () {
        //下滑
        if (that.scrollTop < document.scrollingElement.scrollTop && that.scrollStatus) {
          if (document.scrollingElement.scrollTop < window.innerHeight) {
            that.scrollStatus = false;
            $('html').stop().animate({scrollTop: that.screenHeight}, 600, function () {
              that.scrollStatus = true;
            });
          }
        } else if (that.scrollTop > document.scrollingElement.scrollTop && that.scrollStatus) {//上滑
          if (document.scrollingElement.scrollTop < window.innerHeight) {
            that.scrollStatus = false;
            $('html').stop().animate({scrollTop: 0}, 600, function () {
              that.scrollStatus = true;
            });
          }
        }

        that.scrollTop = document.scrollingElement.scrollTop;


        if (that.scrollTop) {
          $(".header-container").stop().hide(300)
        } else {
          $(".header-container").stop().show(300)
        }
      };


    }

  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #app {
    background-color: #f6f6f6;
  }

  .article {
    position: relative;
    width: 1140px;
    margin: 40px auto 0;
  }

  .article-head {
    overflow: hidden;
    position: relative;
  }

  main {
    width: 66%;
    float: left;
    overflow: hidden;
    z-index: 1;
    clear: both;
  }

  .sidebar {
    width: 32%;
    overflow: hidden;
    float: right;
  }

  .sidebar .toppic {
    width: 100%;
    float: right;
    overflow: hidden;
    position: relative;
    padding: 0;
    background: none;
  }

  .toppic li {
    width: 100%;
    background: #000;
    position: relative;
    overflow: hidden;
    list-style: none;
  }

  .toppic li i {
    display: block;
    opacity: 0.7;
    -moz-transition: all .5s ease;
    -webkit-transition: all .5s ease;
    -ms-transition: all .5s ease;
    -o-transition: all .5s ease;
    transition: all .5s ease;
    overflow: hidden;
  }

  .toppic li i:hover {
    opacity: 1;
  }

  .toppic li i img {
    width: 100%;
    height: 216px;
  }

  .toppic li:last-child {
    margin-top: 19px;
  }

  .toppic li h2 {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    padding: 10px 20px;
    color: #fff;
    display: block;
    font-weight: normal;
    font-size: 16px;
    overflow: hidden;
    background: rgba(0, 0, 0, 0.7);
    text-overflow: ellipsis;
    white-space: nowrap;
    overflow: hidden;
  }

  .toppic li span {
    position: absolute;
    top: 20px;
    left: 20px;
    padding: 6px 10px;
    background: rgba(0, 0, 0, .7);
    font-size: 12px;
    display: block;
    color: #FFF;
    border-radius: 3px;
  }

  .blogs {
    overflow: hidden;
    margin-bottom: 20px;
    padding: 20px;
    background: #FFF;
    -webkit-box-shadow: 0 2px 5px 0 rgba(146, 146, 146, .1);
    -moz-box-shadow: 0 2px 5px 0 rgba(146, 146, 146, .1);
    box-shadow: 0 2px 5px 0 rgba(146, 146, 146, .1);
    -webkit-transition: all 0.6s ease;
    -moz-transition: all 0.6s ease;
    -o-transition: all 0.6s ease;
    transition: all 0.6s ease;
  }

  .blogs .blogtitle {
    margin: 0 0 10px 0;
    font-size: 20px;
    overflow: hidden;
  }

  .blogs .blogtitle a {
    color: #303133;
    text-decoration: none;
  }

  .blogs .blogpic {
    float: left;
    width: 30%;
    max-height: 170px;
    margin-right: 20px;
    display: block;
    overflow: hidden;
  }

  .blogs .blogtext {
    font-size: 14px;
    color: #606266;
    overflow: hidden;
    text-overflow: ellipsis;
    -webkit-box-orient: vertical;
    display: -webkit-box;
    -webkit-line-clamp: 3;
    margin-top: 20px;
  }

  .bloginfo {
    overflow: hidden;
    margin-top: 15px;
  }

  .bloginfo ul li {
    font-size: 12px;
    margin: 0 20px 0 0;
    color: #748594;
    line-height: 1.5;
    display: inline-block;
  }

  .label-tag {
    overflow: hidden;
    margin-top: 20px;
  }

  .label-tag li {
    font-size: 12px;
    display: inline-block;
    line-height: 1;
    vertical-align: baseline;
    background-color: #e8e8e8;
    background-image: none;
    padding: .5833em .833em;
    color: rgba(0, 0, 0, 0.6);
    text-transform: none;
    border: 0 solid transparent;
    border-radius: .28571429rem;
    -webkit-transition: background .1s ease;
    transition: background .1s ease;
    margin-top: 5px;
    margin-bottom: 5px;
  }
</style>
