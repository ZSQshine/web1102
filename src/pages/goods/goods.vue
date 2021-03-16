<template>
  <div>
      <el-button type='primary'>添  加</el-button>
  </div>
</template>

<script>
import vOp from './components/operations'
import vList from './components/list'
export default {
    data(){
        return{
            info:{
                isShow:false,
                isAdd:true,
                title:'添加商品'
            }
        }
    },
    components:{

    }

}
</script>

<style>
.el-button{
    margin: 10px 0;
}
</style>