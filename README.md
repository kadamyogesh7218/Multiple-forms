<!DOCTYPE html>
<html>
  <head> </head>
  <body>
    <header>
      <h2>Already Registered?<u>LOGIN</u> now</h2>
      <!-- image to be used:
       -->

      <form action="" method="post">
        <label for="email">Email : </label>
        <input
          type="email"
          id="email"
          name="email"
          placeholder="abc@gmail.com"
        />
        <label for="pwd">Password : </label>
        <input type="password" id="pwd" name="pwd" />
        <button type="submit">
          <img
            src="https://levelupcollege.com/wp-content/uploads/2021/10/coding-ninjas-logo-white.png"
            height="12px"
          />Login
        </button>
      </form>
    </header>
    <hr />
    <br />

    <main>
      <section>
        <h3><a href="">Coding Ninjas Blogs</a></h3>
        <img src="https://ninjasfiles.s3.amazonaws.com/0000000000001395.png" />
      </section>
      <hr />
      <br />

      <section>
        <h2><u>Registration</u></h2>

        <form action="" method="post">
          <table>
            <tr>
              <td><label for="fname">First Name: </label></td>
              <td><input type="text" id="fname" name="fname" /></td>
            </tr>
            <tr>
              <td><label for="lname">Last Name: </label></td>
              <td><input type="text" id="lname" name="lname" /></td>
            </tr>
            <tr>
              <td>Current Address:</td>
              <td colspan="2">
                <table>
                  <tr>
                    <td><label for="flat">Flat No./House No.: </label></td>
                    <td><input type="text" id="flat" name="flat" /></td>
                  </tr>
                  <tr>
                    <td><label for="locality">Locality: </label></td>
                    <td><input type="text" id="locality" name="locality" /></td>
                  </tr>
                  <tr>
                    <td><label for="city">City: </label></td>
                    <td><input type="text" id="city" name="city" /></td>
                  </tr>
                </table>
              </td>
            </tr>
            <tr>
              <td colspan="2">
                <b>Is Current address and Permanent address same?</b>
              </td>
              <td>
                <input
                  type="radio"
                  name="is-curr-same"
                  id="yes"
                  value="yes"
                  checked
                />
                <input type="radio" name="is-curr-same" id="no" value="no" />
              </td>
            </tr>
            <tr>
              <td><label for="email">Email: </label></td>
              <td><input type="email" id="email" name="email" /></td>
            </tr>
            <tr>
              <td><label for="password">Password: </label></td>
              <td><input type="password" id="password" name="password" /></td>
            </tr>
          </table>
          <br />
          <button type="submit" id="final-sub"><big>Register</big></button>
        </form>
      </section>
    </main>
  </body>
</html>
