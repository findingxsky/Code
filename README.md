#<!DOCTYPE html>
<html ng-app="myApp">
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.8.2/angular.min.js"></script>
<body ng-controller="eventCtrl">
<button ng-click="count = count + 1">Click Me!</button>
<p>Button Clicked: {{count}} times.</p>
<script>
angular.module('myApp', []).controller('eventCtrl', function($scope) {
$scope.count = 0;
});
</script>
</body>
</html> 
