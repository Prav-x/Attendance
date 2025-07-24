# Attendance
<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <META> element to your page <HEAD>.      -->
<!--  If necessary, please modify the charset parameter to specify the        -->
<!--  character set of your HTML page.                                        -->
<!--  ----------------------------------------------------------------------  -->

<META HTTP-EQUIV="Content-type" CONTENT="text/html; charset=UTF-8">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: Please add the following <FORM> element to your page.             -->
<!--  ----------------------------------------------------------------------  -->

<form action="https://webto.salesforce.com/servlet/servlet.WebToCase?encoding=UTF-8&orgId=00DdL00000UmXJx" method="POST">

<input type=hidden name="orgid" value="00DdL00000UmXJx">
<input type=hidden name="retURL" value="http://">

<!--  ----------------------------------------------------------------------  -->
<!--  NOTE: These fields are optional debugging elements. Please uncomment    -->
<!--  these lines if you wish to test in debug mode.                          -->
<!--  <input type="hidden" name="debug" value=1>                              -->
<!--  <input type="hidden" name="debugEmail"                                  -->
<!--  value="praveensenthil488@gmail.com">                                    -->
<!--  ----------------------------------------------------------------------  -->

<label for="name">Contact Name</label><input  id="name" maxlength="80" name="name" size="20" type="text" /><br>

<label for="email">Email</label><input  id="email" maxlength="80" name="email" size="20" type="text" /><br>

<label for="phone">Phone</label><input  id="phone" maxlength="40" name="phone" size="20" type="text" /><br>

<label for="subject">Subject</label><input  id="subject" maxlength="80" name="subject" size="20" type="text" /><br>

<label for="description">Description</label><textarea name="description"></textarea><br>

Student Name:<input  id="00NdL00001DgOFd" maxlength="12" name="00NdL00001DgOFd" size="20" type="text" /><br>

Date of Attendance:<span class="dateInput dateOnlyInput"><input  id="00NdL00001DgO4M" name="00NdL00001DgO4M" size="12" type="text" /></span><br>

Status:<select  id="00NdL00001DgDb9" name="00NdL00001DgDb9" title="Status"><option value="">--None--</option><option value="Present">Present</option>
<option value="Absent">Absent</option>
<option value="OnDuty">OnDuty</option>
</select><br>

<input type="submit" name="submit">

</form>
