<template>
    <div style="padding: 15px;" class="container">
      <form class="md-layout" style="justify-content: center;">
      <md-card class="md-layout-item md-size-100 md-small-size-100">
        <md-card-header>
           <md-icon>settings</md-icon>  <div style="display:inline-block;position: relative; top: 4px; left: 6px;" class="md-title">Setting</div>
        </md-card-header>
          <md-card-content>
                 <form class="md-layout" style="justify-content: center;">
          <div class="md-layout-item md-size-50 md-small-size-100">
          <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"> <md-icon>home</md-icon> ที่อยู่ </label> 
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>  
          <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"> <md-icon>attach_money</md-icon>buy_tax_type</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
           <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>code</md-icon> com_sys_id</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
            <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>account_balance</md-icon> company_name</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
           <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>account_balance</md-icon> eng_name</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
            <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>print</md-icon>fax</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
             <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>phone</md-icon>telephone</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
          </div>
                 <div class="md-layout-item md-size-50 md-small-size-100">
                     <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>add_photo_alternate</md-icon>logo_path</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div> 
          <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>attach_money</md-icon>sale_tax_type</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
           <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>code</md-icon> com_sys_id</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
            <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>code</md-icon> stock_status</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
           <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"> <md-icon>payment</md-icon>tax_number</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
            <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"> <md-icon>payment</md-icon>tax_rate</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>
       
          <div class="md-layout md-gutter">
            <div class="md-layout-item md-size-90 md-small-size-100">
              <md-field >
                <label for="first-name"><md-icon>contacts</md-icon>web_site</label>
                <md-input name="first-name" id="first-name"  />
              </md-field>
            </div>
          </div>

             </div>
              </form>
          </md-card-content>
            <md-card-actions>
          <md-button type="submit" class="md-primary" >ตกลง</md-button>
        </md-card-actions>
      </md-card>

       
      </form>

      </div>
</template>
<script src="../js/setting.js"></script>
<style scoped>
.md-field.md-focused .md-icon, .md-field.md-has-value .md-icon{
  color: blue !important;
  font-size: 20px !important;
 position: relative;
    top: -3px;
} 
</style>