## Message templates

Email参见Mockup文档

### Default
 - Welcome: Welcome to EXFE. Please follow the link to confirm: %URL%  ※Do NOT open if you didn't use EXFE※
   - 欢迎使用EXFE。请打开此链接确认：%URL%  ※如果您未使用EXFE，请勿点击链接※
 - User verification: EXFE identity verification. Please follow the link to confirm: %URL%  ※Do NOT open if you didn't request※
   - EXFE身份验证。请打开此链接确认：%URL%  ※如果您未请求验证，请勿点击链接※
 - Reset password: Reset EXFE password. Please follow the link: %URL%
   - 重设EXFE密码。请打开此链接：%URL%
 - Cross invitation: 
   - Invited: %name1% invited you to "%title%", %time% at %placetitle%. %URL%
     - %name1%邀您加入“%title%”，%time%，%placetitle%。 %URL%
 - Cross update:
   - Combo: "%title%" updated. %time% at %place%.
   - Title: "%oldtitle%" updated to "%newtitle%".
   - Time: "%title%" updated: %time%.
   - Place: "%title%" updated: %placetitle%.
   - Place description: "%title%" at %placetitle% detail updated.
   - Description: "%title" description updated.
   - Invite: "%title%" updated. %name1% invited %name2%, %name3%, %nameN%…. %URL%  // 不用发给邀请者
     - “%title%”更新：%name1%邀请了%name2%、%name3%、%nameN%…。 %URL%  // 不用发给邀请者
   - Join: %name1% joined "%title%" through %name2%'s link. %URL%  //发送对象是邀请者时为“through your link”
     - %name1%通过%name2%的链接加入“%title%”。 %URL%  //发送对象是邀请者时名字%name2%为“您”
   - Response:
     - Combo: "%title%" updated. %name1%, %name2% responsed.
     - Accept: "%title%" updated. %name% accepted.
     - Decline: "%title%" updated. %name% is unavailable.
     - Remove: "%title%" updated. %name% removed.
     - Others: "%title%" updated. %name% pending decision.
 - Conversation: 
   - Post: %name%: %post% %URL%
   - Multi-posts: %count% new posts in "%title%". %URL%
 - Reminding: Reminding: "%title%", %time% at %placetitle%. %URL%
   - 提醒：“%title%”，%time%，%placetitle%。 %URL%
 - Digest: Digest of "%title%" updates: %time% at %placetitle%. %URL%
   - “%title%”更新摘要：%time%，%placetitle%。 %URL%
 - Live contacts: Hello from EXFE, here are contacts you just collected: http://exfe.com/?t=3965
 - Preview: Preview "%title%", please check time and place. %URL%
   - 请预览“%title%”，确认时间和地点。 %URL%
 - RouteX request: %name% is asking your location in: %title%  %URL%  //因为需要短URL暂时未实现
   - %name%请您更新位置：%title%  %URL%

### Phone (SMS) 

注：%URL%使用短验证token格式

 - Welcome: Welcome to EXFE. Please follow the link to confirm: %URL%  \*Do NOT open if you didn't use EXFE\*
 - User verification: EXFE identity verification. Please follow the link to confirm: %URL%  \*Do NOT open if you didn't request\*
   - EXFE身份验证。请打开此链接确认：%URL%  ※如果您未请求验证，请勿点击链接※
   - 注：%URL%使用短验证token格式
 - Update: NULL
 - Conversation: NULL
 - Digest: NULL

### iMessage

注：手机%URL%使用短验证token格式

### iOS/Android push
 - Welcome: NULL

### Twitter
 - Welcomes: NULL
 - User verification: NULL
 - Reset password: NULL
 - Conversation: NULL
