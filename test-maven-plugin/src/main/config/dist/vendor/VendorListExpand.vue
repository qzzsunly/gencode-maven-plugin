<template>
  <div>
    <Row class="expand-row">
 		            <i-col span="6">
            	<span class="expand-key">主键</span>
            	<span class="expand-value">{{ row.id }}</span>
            </i-col>
                    <i-col span="6">
            	<span class="expand-key">供应商编号</span>
            	<span class="expand-value">{{ row.vendorNo }}</span>
            </i-col>
                    <i-col span="6">
            	<span class="expand-key">供应商名称</span>
            	<span class="expand-value">{{ row.vendorName }}</span>
            </i-col>
                    <i-col span="6">
            	<span class="expand-key">供应商地址</span>
            	<span class="expand-value">{{ row.address }}</span>
            </i-col>
                    <i-col span="6">
            	<span class="expand-key">供应商级别</span>
            	<span class="expand-value">{{ row.level }}</span>
            </i-col>
                    <i-col span="6">
            	<span class="expand-key">备注</span>
            	<span class="expand-value">{{ row.remark }}</span>
            </i-col>
            </Row>
  </div>
</template>
<script>
  export default {
    props: {row: Object}
  };
</script>
<style scoped>
  .expand-row {
    margin-bottom: 6px;
  }
  .expand-key {
    font-weight: bold;
    line-height: 25px;
  }
  .expand-value {}
</style>
 