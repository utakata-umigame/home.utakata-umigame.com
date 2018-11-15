<template>
  <section class="container">
    <el-row :gutter="12">
      <el-col :span="8">
        <el-card
          :body-style="{'padding': '0'}">
          <img
            src="https://avatars2.githubusercontent.com/u/43202287?s=200&v=4"
            class="image"
            width="100%"
            alt="aaa">
          <div style="padding: 10px;">
            <a
              href="https://utakata-umigame.com"
              target="_blank"
              class="button--green">
              安定版
            </a>
            <a
              href="https://beta.utakata-umigame.com"
              target="_blank"
              class="button--green">
              ベータ版
            </a>
          </div>
        </el-card>
      </el-col>
      <el-col :span="8">
        <el-card
          :body-style="{'padding': '0'}">
          <img
            src="https://avatars2.githubusercontent.com/u/43202287?s=200&v=4"
            class="image"
            width="100%"
            alt="aaa">
          <div style="padding: 10px;">
            <a
              href="https://gallery.utakata-umigame.com"
              target="_blank"
              class="button--green">
              リンク
            </a>
          </div>
        </el-card>
      </el-col>
      <el-col :span="8">
        <el-card
          :body-style="{'padding': '0'}">
          <img
            src="https://avatars2.githubusercontent.com/u/43202287?s=200&v=4"
            class="image"
            width="100%"
            alt="aaa">
          <div style="padding: 10px;">
            <a
              href="https://wolf.utakata-umigame.com"
              target="_blank"
              class="button--green">
              リンク
            </a>
          </div>
        </el-card>
      </el-col>
    </el-row>
  </section>
</template>
<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
