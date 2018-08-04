# Rails-Ember-Recipes

Connected  Ember Frontend and Rails Api backend.

##### Steps To be followed ->
 
 * Create separate Rails app with ```(--api)``` flag and ember app by typing ```ember new APPNAME```
 * add ``` gem 'active_model_serializers' '~> 0.8.1' ``` to Rails gemfile (Gem version is important) and create [serializer](https://github.com/rails-api/active_model_serializers) and specify the attributes.
 * move into ember app and run ``` ember install active-model-adapter ``` and [follow the instructions here](https://github.com/ember-data/active-model-adapter)
 * run ``` ember serve --proxy http://localhost:3000 ``` and visit [localhost:4200](localhost:4200) on browser

