 <!DOCTYPE html>
<html>
<head>
	<title>Task-1
	</title>
</head>
<body>
	<form>
		<fieldset style="height: 1600px; width: 1000px;">
	

	<font color="Red">*</font> - Doner Required Information<p>
		<b> 1 Donation</b> > 2 Confirmation >  Thank You!
	<h2><font color="Red"> Donar Information</h2></font>
	
		<div>
			<label for="FirstName"><b>First Name:<font color="red">*</font></b></label>
			<input type="FirstName" id="FirstName">
		</div>
		<div>
			<label for="LastName"><b>Last Name:<font color="red">*</font></b></label>
			<input type="LastName" id="LastName">
		</div>
		<div>
			<label for="Company"><b>Company</b></label>
			<input type="Company" id="Company">
		</div>
		<div>
			<label for="Address1"><b>Address 1<font color="red">*</font></b></label>
			<input type="Address1" id="Address1">
		</div>
		<div>
			<label for="Address2"><b>Address 2<font color="red">*</font></b></label>
			<input type="Address2" id="Address2">
		</div>
		<div>
			<label for="City"><b>City<font color="red">*</font></b></label>
			<input type="City" id="City">
		</div>
		<div>
			<label for="state"><b>State<font color="red">*</font></b></label>
			<select name="state">
				<option>Select a State</option>
				<option>California</option>
				<option>Washington</option>
				<option>Texas</option>
				<option>Alberta</option>
				<option>British Collumbia</option>
				<option>Manitoba</option>
			</select>
		</div>
		<div>
			<label for="ZipCode"><b>Zip Code<font color="red">*</font></b></label>
			<input type="ZipCode" id="ZipCode">
		</div>
		<div>
			<label for="country"><b>Country<font color="red">*</font></b></label>
			<select name="state">
				<option>Select a Country</option>
				<option>Canada</option>
				<option>USA</option>
				<option>UK</option>
			</select>
		</div>
		<div>
			<label for="PhoneNo"><b>Phone</b></label>
			<input type="PhoneNo" id="PhoneNo">
		</div>
		<div>
			<label for="fax"><b>Fax</b></label>
			<input type="fax" id="fax">
		</div>
		<div>
			<label for="Email"><b>Email<font color="red">*</font></b></label>
			<input type="Email" name="Email"id="Email">
		</div>
		<div>
			<label for="DonationAmount"><b>Donation Amount<font color="red">*</font></b><br>(Check a button or type in your<br> amount)</label>
			<input type="radio" name="DonationAmount" id="DonationAmount">None
			<input type="radio" name="DonationAmount" id="DonationAmount">$50
			<input type="radio" name="DonationAmount" id="DonationAmount">$75
			<input type="radio" name="DonationAmount" id="DonationAmount">$100
			<input type="radio" name="DonationAmount" id="DonationAmount">$250
			<input type="radio" name="DonationAmount" id="DonationAmount">other
		</div>
		<div>
			<label for="OtherAmount"><b>Other Amount</b></label>
			<input type="OtherAmount" name="OtherAmount"id="OtherAmount">
		</div>
		<div>
			<label for="RecurringDonation"><b>Recurring Donation</b><br>(Check if yes)</label>
			<input type="checkbox" name="RecurringDonation" id="RecurringDonation">I am interested in giving on a regular basis.
		</div>
		<div>
			<label for="MonthlyCreditCard"><b>Monthly Credit Card $</b><br> </label>
			<input type="text" name="MonthlyCreditCard" id="MonthlyCreditCard">For<input type="text" name="MonthlyCreditCard" id="MonthlyCreditCard">Months
		</div>
		<h2><font color="Red">Honorarium and Memorial Donation Information</h2></font>
		<div>
			<label for="d1"><b>I would like to this <br>donation</b></label>
			<input type="radio" name="d1"id="d1">To Honor<br>
			<input type="radio" name="d1"id="d1">In Memory of

		</div>
		<div>
			<label for="Name"><b>Name</b></label>
			<input type="Name" id="Name">
		</div>
		<div>
			<label for="AcknowledgeDonationTo"><b>Acknowledge Donation to</b></label>
			<input type="AcknowledgeDonationTo" id="AcknowledgeDonationTo">
		</div>
		<div>
			<label for="Address"><b>Address</b></label>
			<input type="Address" id="Address">
		</div>
		<div>
			<label for="city"><b>City</b></label>
			<input type="city" id="city">
		</div>
		<div>
			<label for="state"><b>State<font color="red">*</font></b></label>
			<select name="state">
				<option>Select a State</option>
				<option>California</option>
				<option>Manitoba</option>
				<option>Texas</option>
			</select>
		</div>
		<div>
			<label for="Zip"><b>Zip</b></label>
			<input type="Zip" id="Zip">
		</div>
		<h2><font color="Red"> Additional Information</h2></font><br>Please enter your name, company or organization as you would like it to appear in our publications:<br>
		<div>
			<label for="Name"><b>Name</b></label>
			<input type="Name" id="Name">
		</div>
		<div>
			<input type="checkbox" name="c1" id="c1">I would like  my gift to remain anonymous.<br>
			<input type="checkbox" name="c2" id="c2">My employer offer a matching gift program. I will mail the matching gift form.<br>
			<input type="checkbox" name="c3" id="c3">Please save the cost of acknowledging this gift by not mailing a thank you letter.<br>
			 
		</div>
        <div>
		    <label for="comments"><b>Comments</b><br>(Please type any questions or feedback<br>here</label><br>
		    <textarea cols="50" rows="10"></textarea>
	    </div>
	   <div>
	   	<label for="text"><b>How may we contact you ?</b></label>
	   	<input type="checkbox" name="c4" id="c4"> E-mail<br>
	   	<input type="checkbox" name="c5" id="c5"> Postal Mail<br>
	   	<input type="checkbox" name="c6" id="c6"> Telephone<br>
	   	<input type="checkbox" name="c7" id="c7"> Fax<br>
	   	<label>I would like to recieve newslettersc and information about special events by</label><br>
	   	<input type="checkbox"  name="c8" id="c8"> E-mail<br>
	   	<input type="checkbox"  name="c9" id="c9"> Postal Mail<br><p>
	   	<input type="checkbox"  name="10" id="10"> I would like information about volunteering with the<br><p>

      </div>
      <div>
		 <input type="button" value="Reset">
		 <input type="button" value="continue">
		 
	</div><br>
       




</fieldset>
	
	</form>


	</body>
	</html>
