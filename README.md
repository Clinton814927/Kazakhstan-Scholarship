# Kazakhstan-Scholarship
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Kazkhstan</title>
    <style>
      .Luck {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 120px 200px;
        margin-top: -16rem;
      }
      .App {
        justify-content: space-between;
        padding: 30px;
        align-items: center;
      }
      form {
        padding: 5rem 9rem;
        margin-top: -9rem;
}
    </style>
  </head>
  <body>
    <div class="Ward">
      <div class="Oriented">
        <a href="#">Profile</a><br /><br />
        <a href="#">My Applications</a><br /><br />
        <a href="#">Testing</a><br /><br />
        <a href="#">Logout</a><br />
      </div>
      <div class="Luck">
        <div class="App">
          <h1>Creat An Applications</h1>
          <h3>Tel +7(7172)769076</h3>
          <h2>+7 7007760075</h2>
          <h3>Email:info@bolashak.gov.kz</h3>
        </div>
        <div class="King">
          <h3>Kya</h3>
          <h3>Pyc</h3>
          <h3>Eng</h3>
          <h2>Emmanuel James Waribo</h2>
        </div>
      </div>

      <form>
        <h2>Profile</h2>
        <label for="fname">First name</label>
        <input
          type="text"
          id="fname"
          name="fname"
          placeholder="Your name.."
        /><br /><br />
        <hr />
        <label for="lname">Last name</label>
        <input type="text" id="lname" placeholder="Last name" /><br />
        <hr />
        <label>Date of Birth</label><br />
        <input type="date" name="dob" /><br />
        <hr />
        <label>Nationality</label>
        <input type="text" name="Country" placeholder="Nigeria" />
        <hr />
        <label>Passport/identity document number</label>
        <input type="tel" name="phone" /><br />
        <hr />
        <label>Email Address</label><br />
        <input type="email" name="email" /><br />

        <label>Gender</label><br />
        <div class="gender">
          <label><input type="radio" name="gender" value="male" /> Male</label
          ><br />
          <label
            ><input type="radio" name="gender" value="female" /> Female</label
          ><br />
          <hr />
        </div>
        <label>Are you a refugee?</label>
        <div class="citizenship">
          <label><input type="checkbox" name="refugee" /> Yes</label>
        </div>
        <div class="float">
        <label>Upload Passport Document</label>
        <input type="file" class="file-upload" />
        <hr />
        <label>Upload WAEC/High School Result</label>
        <input type="file" class="file-upload" />
        <hr />
        <label>Upload Recommendation Letter</label>
        <input type="file" class="file-upload" />
        <hr />
        <label>Upload Medical Report</label>
        <input type="file" class="file-upload" />
        <hr />
        <label>Upload Application Form (PDF)</label>
        <input type="file" class="file-upload" />

        <hr />
        <label>Motivation Letter</label>
        <textarea
          rows="5"
          placeholder="Write your motivation here (Max 250-500 words)..."
        ></textarea>
        <hr />
        <button type="submit">Submit Application</button>
        <hr />
      </form>
    </div>
  </body>
</html>
