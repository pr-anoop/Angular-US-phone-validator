### Angular US phone number validation module
***
This is a simple Angular module for formatting US phone numbers as this format (xxx) xxx-xxxx.

+ Include the module file into index.html file.

```
<script src="us-phone.min.js"></script>
```

+ Ensure that your Application module specifies 'usPhone' as a dependency.
 
```
angular.module('mobileApp', ['usPhone']);
```

+ Use the directive 'us-phone-directive' in the html input element.

```
<input type="text" us-phone-directive  class="form-control" name="phone" id="phone" ng-model="phone" placeholder="Phone number">
```

Click here for [demo](http://demo.itsanoop.in/angular-us-phone-validation)
