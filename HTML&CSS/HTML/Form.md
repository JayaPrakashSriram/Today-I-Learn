# HTML form,
```
<form action="/submit" method="post">
  <!-- Text Input -->
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required>

  <!-- Text Input 2 -->
  <label for="name">
    <span>Name</span>
    <input type="text" id="name" name="name" required>
  </label>

  <!-- Password Input -->
  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required>

  <!-- Password Input 2 -->
  <label for="password">
    <span>Password</span>
    <input type="password" id="password" name="password" required>
  </label>

  <!-- Radio Buttons -->
  <p>Gender:</p>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label>

  <!-- Age -->
  <label for="age">Age:</label>
  <input type="number" id="password" name="password" required>
 
  <!-- Checkbox -->
  <p>Hobbies:</p>
  <input type="checkbox" id="reading" name="hobbies[]" value="reading">
  <label for="reading">Reading</label>
  <input type="checkbox" id="coding" name="hobbies[]" value="coding">
  <label for="coding">Coding</label>

  <!-- Select Dropdown -->
  <p>Country:</p>
  <select name="country">
    <option value="usa">USA</option>
    <option value="canada">Canada</option>
    <option value="uk">UK</option>
  </select>

  <!-- Select Dropdown 2 -->
  <label> Gender </label>
  <select>
    <optgroup label="Gender">
      <option style='display: none'></option>
      <option>Male</option>
      <option>Female</option>
      <option> TransGender</option>
    </optgroup>
    <optgroup label="Or Else">
      <option>Not Willing to Specified</option>
    </optgroup>
  </select>

  <!-- Textarea -->
  <p>Comments:</p>
  <textarea id="comments" name="comments" rows="4" cols="50"></textarea>

  <!-- Submit Button -->
  <input type="submit" value="Submit">
</form>
```

## Few examples of input type,
### Text Input:
``` <input type="text" name="username" id="username"> ```

### Password Input:
``` <input type="password" name="password" id="password"> ```

### Checkbox:
``` <input type="checkbox" name="subscribe" id="subscribe" value="yes"> ```

### Radio Button:
``` <input type="radio" name="gender" id="male" value="male"> ```
``` <input type="radio" name="gender" id="female" value="female"> ```

### Number Input:
``` <input type="number" name="quantity" id="quantity" min="1" max="10"> ```

### Email Input:
``` <input type="email" name="user_email" id="user_email"> ```

### URL Input:
``` <input type="url" name="website" id="website"> ```

### Date Input:
``` <input type="date" name="event_date" id="event_date"> ```

### Time Input:
``` <input type="time" name="event_time" id="event_time"> ```

### File Input:
``` <input type="file" name="file_upload" id="file_upload"> ```

### Textarea:
``` <textarea name="comments" id="comments" rows="4" cols="50"></textarea> ```

### Submit Button:
``` <input type="submit" value="Submit"> ```

### Reset Button:
``` <input type="reset" value="Reset"> ```

### Hidden Input:
``` <input type="hidden" name="hidden_field" value="hidden_value"> ```

### Color Input:
``` <input type="color" name="color" id="color"> ```
