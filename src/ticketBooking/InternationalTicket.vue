<template>
  <div class="container-fuld" style="background-color:gainsboro">
    <h1 class="fbg">International Ticket Booking Details</h1>
    <form action="/action_page.php" class="was-validated mb-4 mf">
      <div class="pfa">
        <div>
          <p><b>What type of a trip do you need?</b></p>
          <div class="form-check">
            <input
              type="radio"
              class="form-check-input"
              id="radio1"
              name="optradio"
              value="option1"
              checked
            />One way
            <label class="form-check-label" for="radio1"></label>
          </div>
          <div class="form-check">
            <input
              type="radio"
              class="form-check-input"
              id="radio2"
              name="optradio"
              value="option2"
            />Two way
            <label class="form-check-label" for="radio2"></label>
          </div>
        </div>
        <div class="mb-3">
          <label for="fromCountry" class="form-label"><b>From Country:</b></label>
          <input
            type="text"
            class="form-control"
            id="fromCountry"
            placeholder="Enter Country Name"
            name="fromCountry"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="mb-3">
          <label for="ToCountry" class="form-label"><b>To Counrty:</b></label>
          <input
            type="text"
            class="form-control"
            id="ToCountry"
            placeholder="Enter Country Name"
            name="ToCountry"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="mb-3">
          <label for="dat" class="form-label"><b>Date:</b></label>
          <input
            type="date"
            class="form-control"
            id="dat"
            placeholder="Enter Your Ticket Booking Date"
            name="dat"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div>
          <p><b>Title</b></p>
          <div class="form-check">
            <input
              type="radio"
              class="form-check-input"
              id="radio3"
              name="optradio_two"
              value="option2"
              checked
            />Mr
            <label class="form-check-label" for="radio3"></label>
          </div>
          <div class="form-check">
            <input
              type="radio"
              class="form-check-input"
              id="radio4"
              name="optradio_two"
              value="option2"
            />Ms
            <label class="form-check-label" for="radio4"></label>
          </div>
          <div class="form-check">
            <input
              type="radio"
              class="form-check-input"
              id="radio5"
              name="optradio_two"
              value="option2"
            />Mrs
            <label class="form-check-label" for="radio6"></label>
          </div>
        </div>
        <div class="mb-3">
          <label for="FirstName" class="form-label"><b>First Name:</b></label>
          <input
            type="text"
            class="form-control"
            id="FirstName"
            placeholder="Enter First Name"
            name="FirstName"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="mb-3">
          <label for="LastName" class="form-label"><b>Last Name:</b></label>
          <input
            type="text"
            class="form-control"
            id="LastName"
            placeholder="Enter Last Name"
            name="LastName"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div>
          <p><b>Gender:</b></p>
          <div class="form-check">
            <input
              type="radio"
              class="form-check-input"
              id="radio6"
              name="optradio_three"
              value="option3"
              checked
            />Male
            <label class="form-check-label" for="radio3"></label>
          </div>
          <div class="form-check">
            <input
              type="radio"
              class="form-check-input"
              id="radio7"
              name="optradio_three"
              value="option3"
            />Female
            <label class="form-check-label" for="radio4"></label>
          </div>
          <div class="form-check">
            <input
              type="radio"
              class="form-check-input"
              id="radio8"
              name="optradio_three"
              value="option3"
            />Other
            <label class="form-check-label" for="radio6"></label>
          </div>
        </div>
        <div class="mb-3">
          <label for="DateOfBirth" class="form-label"><b>Date of Birth:</b></label>
          <input
            type="date"
            class="form-control"
            id="DateOfBirth"
            placeholder="Enter Your Birth Date"
            name="DateOfBirth"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="mb-3">
          <label for="Nationality" class="form-label"><b>Nationality:</b></label>
          <input
            type="text"
            class="form-control"
            id="Nationality"
            placeholder="Enter Your Nationality"
            name="Nationality"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="mb-3">
          <label for="PassportNumber" class="form-label"><b>Passport Number:</b></label>
          <input
            type="text"
            class="form-control"
            id="PassportNumber"
            placeholder="Enter Your Passport Number"
            name="PassportNumber"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="mb-3">
          <label for="PassportIssueDate" class="form-label"><b>Passport Issue Date:</b></label>
          <input
            type="date"
            class="form-control"
            id="PassportIssueDate"
            placeholder="Enter Your Passport Issue Date"
            name="PassportIssueDate"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="mb-3">
          <label for="pwd" class="form-label"><b>PassportExpireDate:</b></label>
          <input
            type="date"
            class="form-control"
            id="PassportExpireDate"
            placeholder="Enter Your Passport Expire Date"
            name="PassportExpireDate"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="mb-3">
          <label for="PhoneNumber" class="form-label"><b>Phone Number:</b></label>
          <input
            type="number"
            class="form-control"
            id="PhoneNumber"
            placeholder="Enter Your Phone Number"
            name="PhoneNumber"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="mb-3">
          <label for="ema" class="form-label"><b>Email:</b></label>
          <input
            type="email"
            class="form-control"
            id="ema"
            placeholder="Enter Your Email"
            name="ema"
            required
          />
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Please fill out this field.</div>
        </div>
        <div class="form-check mb-3">
          <input
            class="form-check-input"
            type="checkbox"
            id="myCheck"
            name="remember"
            required
          />
          <label class="form-check-label" for="myCheck"
            >I agree for terms and conditions</label
          >
          <div class="valid-feedback">Valid.</div>
          <div class="invalid-feedback">Check this checkbox to continue.</div>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  data(){
    return{
    }
  }
}
</script>
<style scoped>
.fbg {
  text-align: center;
  padding: 2%;
}
.mf {
  margin: auto;
  margin-top: 2%;
  width: 90%;
  background-color: aliceblue;
}
.pfa {
  padding: 3%;
}
.tc{
  color: aliceblue;
}
</style>