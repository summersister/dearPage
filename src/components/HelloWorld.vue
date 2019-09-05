<template>
    <div>
      <Layout>
        <Header :style="{padding: 0}" class="layout-header-bar">header</Header>
        <Content :style="{margin: '20px', background: '#fff', minHeight: '460px', align:'center'}">
          <Row>
            <Card class="card">
              <p slot="title">The standard card</p>
              <div class="col2_left j_threadlist_li_left">
                <span class="threadlist_rep_num" title="回复">8</span>
              </div>
              <div class="col2_right j_threadlist_li_right ">
                <div class="threadlist_lz clearfix">
                  <div class="threadlist_title pull_left j_th_tit  member_thread_title_frs ">
                    <a rel="noreferrer" href="/p/6246476711" title="匹配2=3不要下路" target="_blank" class="j_th_tit ">匹配2=3不要下路</a>
                  </div>
                  <div class="threadlist_author pull_right">

                    <span class="tb_icon_author no_icon_author" title="主题作者">
                      <span class="pre_icon_wrap pre_icon_wrap_theme1 frs_bright_preicon">
                        <a class="icon_tbworld icon-crown-year-v2" target="_blank" title="贴吧超级会员"></a>
                      </span>
                      <span class="frs-author-name-wrap">
                        <a rel="noreferrer" target="_blank">幼宠宠</a>
                      </span>
                      <span class="icon_wrap  icon_wrap_theme1 frs_bright_icons ">
                        <a style="background: url(//tb1.bdstatic.com/tb/cms/com/icon/102_14.png?stamp=1567420751) no-repeat -900px  0;top:0px;left:0px" 
                         target="_blank" class="j_icon_slot" title="狮子座印记" locate="shizi_1#icon">
                        </a>
                      </span>
                    </span>
                    <span class="pull-right is_show_create_time" title="创建时间">20:38</span>
                  </div>
                </div>
              </div>
            </Card>
            <Card class="card">
              <p slot="title">The standard card</p>
              <p>Content of card</p>
              <p>Content of card</p>
              <p>Content of card</p>
            </Card>
          </Row>
        </Content>
        <!-- <Footer :style="{padding: 0}" class="layout-header-bar">footer</Footer> -->
      </Layout>
    </div>
</template>

<style scoped>
.threadlist_bright .threadlist_author a {
    color: #999;
    text-decoration: none;
}
.threadlist_bright .threadlist_lz .no_icon_author {
    width: 156px;
}
.threadlist_bright .t_con img, .threadlist_bright .t_con i, .threadlist_bright .t_con a, .threadlist_bright .t_con span, .threadlist_bright .t_con em, .threadlist_bright .t_con strong, .threadlist_bright .t_con b, .threadlist_bright .t_con input, .threadlist_bright .t_con button {
    vertical-align: middle;
}
.is_show_create_time {
    display: none;
}
    .member_thread_title_frs a {
        color: #f74d4a!important;
    }
    .threadlist_author {
        width: 165px;
        color: #999;
    }
    .pull-right {
        float: right!important;
    }
    .pull_left, .pull-left {
        float: left!important;
    }
    .threadlist_title {
        width: 460px;
    }
    .threadlist_title {
        font-size: 14px;
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
    }
    .col2-right {
        position: relative;
        min-height: 1px;
    }
    .col2-left {
        float: left;
        min-height: 1px;
    }
    .threadlist_rep_num {
        display: inline-block;
        width: 50px;
        height: 30px;
        line-height: 26px;
        margin-right: 20px;
        text-align: center;
        background: url('../assets/img/f_reply_bg_89030dc.png') no-repeat;
    }
    .card{
        width: 70%;
        position: relative;
        left: 0;
        right: 0;
        margin: 0 auto;
    }
    .layout-header-bar{
        background: #fff;
        box-shadow: 0 1px 1px rgba(0,0,0,.1);
    }
</style>