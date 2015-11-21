# Theme Objects


> Example form usage

```html
{{form.start}}
  <div class="form-group">
    <label>Email address</label>
    {{form.username}}
  </div>
  <div class="form-group">
    <label>Password</label>
    {{form.password('some-class')}}
  </div>
  {{form.submit('Log Me In', 'btn btn-default')}}
{{form.end}}
```

### Form Objects
All form objects contain the following:

### form.start
Renders the start of the form.

### form.end
Renders the end of the form

### form.submit([label])
Renders a submit button

## login_form


Used to log a user into their account.

<aside class="notice">
Only can be used on <code>customers/login.twig</code>.
</aside>



```
form.username
form.password
```

### form.username
renders the form username text element.

### form.password
renders the form password element.





## reset_password_form


Used to log a user into their account.

<aside class="notice">
Only can be used on <code>customers/reset-password.twig</code>.
</aside>



```
form.username
```

### form.username
renders the form username text element.




## customer_form

<aside class="notice">
Only can be used on <code>customers/register.twig</code>.
</aside>

### form.email
renders the form email text element.

### form.password
renders the form password text element.

### form.passwordRetype
renders the form password retype text element.


### form.firstName
renders the form first name text element.

### form.lastName
renders the form last name element.

### form.address1
renders the form address1 element.

### form.address2
renders the form address2 element.

### form.city
renders the form city element.

### form.stateProvince
renders the form state/province select element.

### form.postalCode
renders the form postal code element.

### form.phone
renders the form postal code element.


## shipping_form

