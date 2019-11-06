# Registration<!DOCTYPE html>
<html>
<head>
<title>Patient Registration form</title>
</head>

<body>
<form method="post">
<table width="600" align="center" border="1" cellspacing="5" cellpadding="5">
<tr>
<td colspan="2"><?php echo @$error; ?></td>
</tr>
  <tr>
    <td width="230">Enter Full Names </td>
    <td width="329"><input type="text" name="name"/></td>
  </tr>
 
  <tr>
    <td>Date Of Birth </td>
    <td><input type="text" name="DOB"/></td>
  </tr>
 
   <tr>
    <td>Gender </td>
    <td>
<select name="Gender">
<option value="">Gender</option>
<option>Male</option>
<option>Female</option>
<option>Other</option>
</select>
</td>
  </tr>
 
  <tr>
    <td>Enter Your Mobile </td>
    <td><input type="text" name="mobile"/></td>
  </tr>
 
  <tr>
    <td>Marital Status</td>
    <td>
<select name="Marital Status">
<option value="">Marital Status</option>
<option>Single</option>
<option>Married</option>

</select>
</td>
  </tr>
  <tr>
    <td>Enter Your Email </td>
    <td><input type="text" name="email"/></td>
  </tr>
 
  <tr>
    <td>Enter Your Password </td>
    <td><input type="password" name="pass"/></td>
  </tr>

  <tr>
    <td colspan="2" align="center">
<input type="submit" name="register" value="Register Me"/></td>
  </tr>
</table>

</form>
</body>
</html>
