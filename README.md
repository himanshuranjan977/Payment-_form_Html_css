# Payment-_form_Html_css

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width,
			initial-scale=1.0" />
    <title>PAYMENTS FORM</title>
    <link rel="stylesheet" href="Payment.css">
</head>

<body>
    <form action="">
        <div class="container">
            <div class="main-content">
                
            </div>

            <div class="centre-content">
                <h1>Payment Forms</h1>
                <h6>-designed by HIMANSHU RANJAN</h6>
                <h4 class="">2499/-</h4>
                <p class="course">
                    Buy Web Development course self-paced now!
                </p>
            </div>

            <div class="last-content">
                <button type="button" class="pay-now-btn">
                    <label for="Apply coupan"> Apply Coupons : </label>
                    <select name="Apply Coupons" id="Apply Coupons">
                        <option value="">--Apply any one them--</option>
                        <option value="">Kabita100</option>
                        <option value="" select>HR100</option>
                        <option value="" select>Non of them</option>
                    </select>
                </button>
                <button type="button" class="pay-now-btn">
                    <label for="Payment option">Payment option : </label>
                    <select>
                        <option value="">--Apply any of them</option>
                        <option value="">Debit Card</option>
                        <option value="">Net banking</option>
                        <option value="">Master Card</option>
                    </select>
                </button>


            </div>

            <div class="card-details">
                <p>Pay using above option shown</p>

                <div class="card-number">
                    <label> Card Number </label>
                    <input type="number" id="cvv" inputmode="numeric" pattern="[0-9\s]{13,16}" autocomplete="cc-number" maxlength="16" placeholder="xxxx xxxx xxxx xxxx" required name="placeholder">

                     
                </div>

                <div class="date-number">
                    <label> Expiry Date </label>
                    <input type="number" id="date-number"  inputmode ="numeric" pattern="[0-9\s]{4}" autocomplete="E date" maxlength="4" placeholder="xx-xx "  required name="placeholder">

                    
                <div class="cvv-number">
                    <label> CVV number </label>
                    <input  id="cvv-number"type ="number " inputmode="numeric"  pattern="[0-9]{3}" autocomplete=" cvv number" maxlength="3" placeholder="xxx  "  required name="placeholder">
                    
                </div>
                <div class="nameholder-number">
                    <label> Card Holder name </label>
                    <input type="text" id="fname"  inputmode="kana-name" placeholder="Enter your Name" required name="placeholder" >
                </div>
                <div>
                    <button type="    reset" value=" reset" class="reset-now">
                        Reset
                    </button>
                    <button type="submit" class="submit-now-btn">
                        submit
                    </button>



                </div>

                

            </div>
            
        </div>
        <div>
            <h4>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;Thanku for Waching my new project</h4>
            
        </div>
    </form>
</body>

</html>
