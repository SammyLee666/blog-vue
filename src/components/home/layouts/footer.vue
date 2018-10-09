<template>
  <footer class="footer">
    <div class="footer-container">
      <ul>
        <li>
          <el-tooltip class="item" effect="dark" content="GitHub" placement="top">
            <a href="">
              <img src="/static/img/github.png" alt="">
            </a>
          </el-tooltip>
        </li>
      </ul>
    </div>
    <div class="copy-right"><span>© 2018. Powered By Sammy Lee</span></div>
  </footer>
</template>

<script>
  export default {
    name: "foote"
  }
</script>

<style scoped>
  .footer {
    background: #909399;
    margin-top: 40px;
  }

  .footer-container {
    width: 1140px;
    padding: 25px 0 10px 0;
    text-align: center;
    margin: 0 auto;
  }

  .footer-container img {
    width: 24px;
  }

  .footer-container li {
    display: inline-block;
  }

  .copy-right {
    padding-bottom: 12px;
    text-align: center;
    color: #fff;
  }
</style>
