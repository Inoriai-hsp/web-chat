<template>
  <el-container class="main">
    <el-aside width="35%" class="left">
        <div class="user">
          <el-avatar :size="60" src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"></el-avatar>
          <div class="profile">
            <span>昵称</span>
            <span>签名</span>
          </div>
        </div>
        <el-form class="search">
          <el-form-item>
            <el-input></el-input>
          </el-form-item>
          <!-- <el-form-item>
            <el-button type="primary" icon="el-icon-search">搜索</el-button>
          </el-form-item> -->
          <!-- <el-form-item>
            <el-button type="success">词云</el-button>
            <el-button icon="el-icon-plus"></el-button>
          </el-form-item> -->
        </el-form>
        <div class="friends">

        </div>
    </el-aside>
    <el-main class="right"></el-main>
  </el-container>
</template>

<!-- <template>
  <el-container class="main">
    main
  </el-container>
</template> -->

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  data() {
    return {
      friendsData: [
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        },
        {
          id: 1
        }
      ]
    }
  }
}
</script>

<style>
.options {
  height: 50px;
  line-height: 50px;
  background-color: pink;
}

.latestChat {
  float: left;
  font-size: 14px;
  line-height: 30px;
  height: 60px;
}

.latestChat>span {
  display: block;
}

.chat {
  height: 60px;
}

.friends {
  margin: 10px;
  height: 600px;
  background-color: pink;
}

.search {
  margin: 10px;
}

.profile {
  float: left;
  font-size: 14px;
  line-height: 30px;
  height: 80px;
}

.profile>span {
  display: block;
}

.el-avatar {
  float: left;
  /* margin: 0 20px 0 80px; */
  margin-right: 20px;
}

.user {
  margin: 10px;
  height: 60px;
  /* line-height: 80px; */
  /* background-color: blue; */
}

.el-aside>.el-card {
  margin: 30px 0;
  height: 60px;
}

.right {
  background-color: #ffffff;
  border-radius: 10px;
}

.left {
  box-sizing: border-box;
  /* padding: 30px 40px 20px; */
  margin-right: 10px;
  border-radius: 10px;
  background-color: #ffffff;
}

.main {
  height: 800px;
  width: 1200px;
  margin: 80px auto;
}
</style>