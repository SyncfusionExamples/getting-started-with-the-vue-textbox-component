<script>
import { TextBoxComponent } from "@syncfusion/ej2-vue-inputs";

export default {
 
    components: {
        'ejs-textbox' : TextBoxComponent,
    }
}
</script>
<template>
<div>
<ejs-textbox width="160px" :multiline="true" readonly="true" value="John" :enabled="false"
></ejs-textbox>
<!-- <div >
<ejs-textbox width="160px" placeholder="Auto" cssClass="e-warning" floatLabelType="Auto">  
</ejs-textbox>
</div>
<div>
<ejs-textbox width="160px" placeholder="Never" cssClass="e-success" floatLabelType="Never">     
</ejs-textbox>
</div> -->
</div> 
</template>
<style>
 @import "../node_modules/@syncfusion/ej2-base/styles/fluent.css";
@import "../node_modules/@syncfusion/ej2-vue-inputs/styles/fluent.css";

.e-control-wrapper, .e-input-group{
  margin: 20px;
}
.textbox{
  padding-bottom: 160px ;
 }
</style>