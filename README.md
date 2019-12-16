1.create sample test spec which makes use of mockdata.
2.Create a method to fetch data from service/api

use:
Mock Service
HTTP

execute:
ng test --code-coverage

routerLink="/client/Customizations" routerLinkActive="active"

  <div class="client-nav-item">
    <a class="client-nav-item-link" routerLink="/client/settings/myaccount" routerLinkActive="active">
      <!--<img src="/assets/images/settings.png" width="24px" height="24px" />--><span style="position:absolute;left: 16px">Settings</span>
    </a>
  </div>

.client-nav-item-link{
  /*width: 224px;*/
  height: 56px;
  line-height: 40px;
  border-radius: 0px;
  background-color: transparent;
  margin: 0px auto;
  display: block;
  color: #9ea8b9;
  font-size: 20px;
  padding: 10px 30px;
  
}

.client-nav-item-link:hover{
  text-decoration-line: none;
  
}

.client-nav-item-link.active{
  background-color: white;
  color: #1f6efe;
  border-left:4px solid #1f6efe;
}  	
