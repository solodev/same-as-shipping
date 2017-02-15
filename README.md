# same-as-shipping
Making the consumer experience online as easy as possible is essential to your success online. In this article, [Solodev](https://www.solodev.com/) will teach you how to add "same as billing" functionality to your shopping cart which will populate the users billing info into their shipping info form.

## Tutorials

For detailed instructions, view Solodev's [Adding Same as Billing Functionality to your Website](https://www.solodev.com/blog/web-design/adding-same-as-billing-functionality-to-your-shopping-cart.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/bx85nxjb/).

## HTML

The same-as-shipping form contains the following HTML markup.

```
<div class="container">


<div class="ship-bill-info section">
   <div class="title-box">
      <div class="row">
         <div class="col-sm-6">
            <h3>
               Shipping & Billing Information
            </h3>
         </div>
      
      </div>
   </div>
   <div class="row">
      <div class="col-md-6">
         <div class="ship-info-form">
            <div class="row">
               <div class="col-md-6">
                  <h4>
                     Shipping Information
                  </h4>
               </div>
               <div class="col-md-6">
                  &nbsp;
               </div>
            </div>
            <div class="row">
               <div class="col-md-6">
                  <div class="form-group">
                     <label for="shippingfname"><span>*</span> First Name</label> <input id="shippingfname" name="shippingfname" type="text" data-validation="required" value="">
                  </div>
               </div>
               <div class="col-md-6">
                  <div class="form-group">
                     <label for="shippinglname"><span>*</span> Last Name</label> <input id="shippinglname" name="shippinglname" type="text" data-validation="required" value="">
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-12">
                  <div class="form-group">
                     <label for="shippingstreet"><span>*</span> Street Address</label> <input id="shippingstreet" name="shippingstreet" type="text" data-validation="required" value="">
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-4">
                  <div class="form-group">
                     <label for="shippingsuite">Suite/Apt #</label> <input id="shippingsuite" name="shippingsuite" type="text" value="">
                  </div>
               </div>
               <div class="col-md-8">
                  <div class="form-group">
                     <label for="shippingcity"><span>*</span> City</label> <input id="shippingcity" name="shippingcity" type="text" data-validation="required" value="">
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-4">
                  <div class="form-group">
                     <label for="shippingstate"><span>*</span> State</label> 
                     <select name="shippingstate" id="shippingstate" data-validation="required">
                        <option value="">
                           Select
                        </option>
                        <option value="AL">
                           Alabama
                        </option>
                        <option value="AK">
                           Alaska
                        </option>
                        <option value="AZ">
                           Arizona
                        </option>
                        <option value="AR">
                           Arkansas
                        </option>
                        <option value="CA">
                           California
                        </option>
                        <option value="CO">
                           Colorado
                        </option>
                        <option value="CT">
                           Connecticut
                        </option>
                        <option value="DE">
                           Delaware
                        </option>
                        <option value="DC">
                           District Of Columbia
                        </option>
                        <option value="FL">
                           Florida
                        </option>
                        <option value="GA">
                           Georgia
                        </option>
                        <option value="HI">
                           Hawaii
                        </option>
                        <option value="ID">
                           Idaho
                        </option>
                        <option value="IL">
                           Illinois
                        </option>
                        <option value="IN">
                           Indiana
                        </option>
                        <option value="IA">
                           Iowa
                        </option>
                        <option value="KS">
                           Kansas
                        </option>
                        <option value="KY">
                           Kentucky
                        </option>
                        <option value="LA">
                           Louisiana
                        </option>
                        <option value="ME">
                           Maine
                        </option>
                        <option value="MD">
                           Maryland
                        </option>
                        <option value="MA">
                           Massachusetts
                        </option>
                        <option value="MI">
                           Michigan
                        </option>
                        <option value="MN">
                           Minnesota
                        </option>
                        <option value="MS">
                           Mississippi
                        </option>
                        <option value="MO">
                           Missouri
                        </option>
                        <option value="MT">
                           Montana
                        </option>
                        <option value="NE">
                           Nebraska
                        </option>
                        <option value="NV">
                           Nevada
                        </option>
                        <option value="NH">
                           New Hampshire
                        </option>
                        <option value="NJ">
                           New Jersey
                        </option>
                        <option value="NM">
                           New Mexico
                        </option>
                        <option value="NY">
                           New York
                        </option>
                        <option value="NC">
                           North Carolina
                        </option>
                        <option value="ND">
                           North Dakota
                        </option>
                        <option value="OH">
                           Ohio
                        </option>
                        <option value="OK">
                           Oklahoma
                        </option>
                        <option value="OR">
                           Oregon
                        </option>
                        <option value="PA">
                           Pennsylvania
                        </option>
                        <option value="RI">
                           Rhode Island
                        </option>
                        <option value="SC">
                           South Carolina
                        </option>
                        <option value="SD">
                           South Dakota
                        </option>
                        <option value="TN">
                           Tennessee
                        </option>
                        <option value="TX">
                           Texas
                        </option>
                        <option value="UT">
                           Utah
                        </option>
                        <option value="VT">
                           Vermont
                        </option>
                        <option value="VA">
                           Virginia
                        </option>
                        <option value="WA">
                           Washington
                        </option>
                        <option value="WV">
                           West Virginia
                        </option>
                        <option value="WI">
                           Wisconsin
                        </option>
                        <option value="WY">
                           Wyoming
                        </option>
                     </select>
                  </div>
               </div>
               <div class="col-md-4">
                  <div class="form-group">
                     <label for="shippingzcode"><span>*</span> Zip Code</label> <input id="shippingzcode" name="shippingzcode" type="text" data-validation="required" value="">
                  </div>
               </div>
               <div class="col-md-4">
                  <div class="form-group">
                     <label for="shippingphone"><span>*</span> Phone</label> <input id="shippingphone" name="shippingphone" type="text" data-validation="required custom" data-validation-regexp="^((([0-9]{3}))|([0-9]{3}))[-\s\.]?[0-9]{3}[-\s\.]?[0-9]{4}$" value="">
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-12">
                  <div class="form-group">
                     <label for="shippingemail"><span>*</span> Email Address</label> <input id="shippingemail" name="shippingemail" type="text" data-validation="required email" value="">
                  </div>
               </div>
            </div>
         </div>
      </div>
      <div class="col-md-6">
         <div class="ship-info-form">
            <div class="row">
               <div class="col-md-6">
                  <h4>
                     Billing Information
                  </h4>
               </div>
               <div class="col-md-6">
                  <div class="checkbox">
                     <input type="checkbox" class="checkbox-cart" id="use-shipping-check" name="same-shipping-check" value="same-shipping-check"> <label for="use-shipping-check" class="label-cart">Same as Shipping</label>
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-6">
                  <div class="form-group">
                     <label for="billingfname"><span>*</span> First Name</label> <input id="billingfname" name="billingfname" type="text" data-validation="required" value="">
                  </div>
               </div>
               <div class="col-md-6">
                  <div class="form-group">
                     <label for="billinglname"><span>*</span> Last Name</label> <input id="billinglname" name="billinglname" type="text" data-validation="required" value="">
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-12">
                  <div class="form-group">
                     <label for="billingstreet"><span>*</span> Street Address</label> <input id="billingstreet" name="billingstreet" type="text" data-validation="required" value="">
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-4">
                  <div class="form-group">
                     <label for="billingsuite">Suite/Apt #</label> <input id="billingsuite" name="billingsuite" type="text" value="">
                  </div>
               </div>
               <div class="col-md-8">
                  <div class="form-group">
                     <label for="billingcity"><span>*</span> City</label> <input id="billingcity" name="billingcity" type="text" data-validation="required" value="">
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-4">
                  <div class="form-group">
                     <label for="billingstate"><span>*</span> State</label> 
                     <select name="billingstate" id="billingstate" data-validation="required">
                        <option value="">
                           Select
                        </option>
                        <option value="AL">
                           Alabama
                        </option>
                        <option value="AK">
                           Alaska
                        </option>
                        <option value="AZ">
                           Arizona
                        </option>
                        <option value="AR">
                           Arkansas
                        </option>
                        <option value="CA">
                           California
                        </option>
                        <option value="CO">
                           Colorado
                        </option>
                        <option value="CT">
                           Connecticut
                        </option>
                        <option value="DE">
                           Delaware
                        </option>
                        <option value="DC">
                           District Of Columbia
                        </option>
                        <option value="FL">
                           Florida
                        </option>
                        <option value="GA">
                           Georgia
                        </option>
                        <option value="HI">
                           Hawaii
                        </option>
                        <option value="ID">
                           Idaho
                        </option>
                        <option value="IL">
                           Illinois
                        </option>
                        <option value="IN">
                           Indiana
                        </option>
                        <option value="IA">
                           Iowa
                        </option>
                        <option value="KS">
                           Kansas
                        </option>
                        <option value="KY">
                           Kentucky
                        </option>
                        <option value="LA">
                           Louisiana
                        </option>
                        <option value="ME">
                           Maine
                        </option>
                        <option value="MD">
                           Maryland
                        </option>
                        <option value="MA">
                           Massachusetts
                        </option>
                        <option value="MI">
                           Michigan
                        </option>
                        <option value="MN">
                           Minnesota
                        </option>
                        <option value="MS">
                           Mississippi
                        </option>
                        <option value="MO">
                           Missouri
                        </option>
                        <option value="MT">
                           Montana
                        </option>
                        <option value="NE">
                           Nebraska
                        </option>
                        <option value="NV">
                           Nevada
                        </option>
                        <option value="NH">
                           New Hampshire
                        </option>
                        <option value="NJ">
                           New Jersey
                        </option>
                        <option value="NM">
                           New Mexico
                        </option>
                        <option value="NY">
                           New York
                        </option>
                        <option value="NC">
                           North Carolina
                        </option>
                        <option value="ND">
                           North Dakota
                        </option>
                        <option value="OH">
                           Ohio
                        </option>
                        <option value="OK">
                           Oklahoma
                        </option>
                        <option value="OR">
                           Oregon
                        </option>
                        <option value="PA">
                           Pennsylvania
                        </option>
                        <option value="RI">
                           Rhode Island
                        </option>
                        <option value="SC">
                           South Carolina
                        </option>
                        <option value="SD">
                           South Dakota
                        </option>
                        <option value="TN">
                           Tennessee
                        </option>
                        <option value="TX">
                           Texas
                        </option>
                        <option value="UT">
                           Utah
                        </option>
                        <option value="VT">
                           Vermont
                        </option>
                        <option value="VA">
                           Virginia
                        </option>
                        <option value="WA">
                           Washington
                        </option>
                        <option value="WV">
                           West Virginia
                        </option>
                        <option value="WI">
                           Wisconsin
                        </option>
                        <option value="WY">
                           Wyoming
                        </option>
                     </select>
                  </div>
               </div>
               <div class="col-md-4">
                  <div class="form-group">
                     <label for="billingzcode"><span>*</span> Zip Code</label> <input id="billingzcode" name="billingzcode" type="text" data-validation="required" value="">
                  </div>
               </div>
               <div class="col-md-4">
                  <div class="form-group">
                     <label for="billingphone"><span>*</span> Phone</label> <input id="billingphone" name="billingphone" type="text" data-validation="required custom" data-validation-regexp="^((([0-9]{3}))|([0-9]{3}))[-\s\.]?[0-9]{3}[-\s\.]?[0-9]{4}$" value="">
                  </div>
               </div>
            </div>
            <div class="row">
               <div class="col-md-12">
                  <div class="form-group">
                     <label for="billingemail"><span>*</span> Email Address</label> <input id="billingemail" name="billingemail" type="text" data-validation="required email" value="">
                  </div>
               </div>
            </div>
         </div>
      </div>
   </div>
</div>
</div>
```
## CSS

All required CSS is in the file ship-bill.css

## JavaScript

This tutorial utilizes the JavaScript below.

```
$("#use-shipping-check").click(function(){
      if(this.checked) {
        $("#billingfname").val($("#shippingfname").val()).change().blur();
        $("#billinglname").val($("#shippinglname").val()).change().blur();
        $("#billingstreet").val($("#shippingstreet").val()).change().blur();
        $("#billingsuite").val($("#shippingsuite").val()).change().blur();
        $("#billingcity").val($("#shippingcity").val()).change().blur();
        $("#billingstate").val($("#shippingstate").val()).change().blur();
        $("#billingzcode").val($("#shippingzcode").val()).change().blur();
        $("#billingphone").val($("#shippingphone").val()).change().blur();
        $("#billingemail").val($("#shippingemail").val()).change().blur();
      }else{
        $("#billingfname").val("").change().blur();
        $("#billinglname").val("").change().blur();
        $("#billingstreet").val("").change().blur();
        $("#billingsuite").val("").change().blur();
        $("#billingcity").val("").change().blur();
        $("#billingstate").val("").change().blur();
        $("#billingzcode").val("").change().blur();
        $("#billingphone").val("").change().blur();
        $("#billingemail").val("").change().blur();
      }
  });
```

## External Includes

This tutorial utilizes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="ship-bill.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script src="ship-bill.js"></script>
```
