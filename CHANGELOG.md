# 0.5.0

### Revamp of API to provide deeper integration with AngularJS.

* Changed directive to `kendo-widget-name` instead of `data-role` declaration
* Configuration options object can now be passed from $scope using `k-options` attribute
* Events are declared with a preceding `k-on` as attributes and take in a `kendoEvent` argument to capture the fired event from Kendo UI
* All widgets now work with `ng-model` for two way binding to scope
* A widget reference can be assigned to a scope variable by passing the name into the primary directive attribute

# .0.0.1

Initial release is a passthrough for Kendo UI declarative initialization using a simple directive.



