# CouchRest Model ORM for Devise

It's just a ORM for integrate Devise and CouchDB.

# CouchDB

Apache CouchDB is a document-oriented database that can be queried and indexed in a MapReduce fashion using JavaScript.
[http://couchdb.apache.org/]

# CouchRest Model

CouchRest Models adds additional functionality to the standard CouchRest Document class such as setting properties, callbacks, typecasting, and validations.
[http://github.com/couchrest/couchrest_model/]

# Devise

Devise is a flexible authentication solution for Rails based on Warden. Devise supports ActiveRecord (default) and Mongoid. To choose other ORM, you just need to require it in the initializer file.
[http://github.com/plataformatec/devise/]

## Usage

1 - Create a Rails Application
2 - Configure Devise
3 - Put this file ([http://github.com/lucasrenan/CouchRest-Model-ORM-for-Devise/blob/master/couchrestmodel.rb]) into the lib directory in your rails application
4 - Change the require path in devise.rb initializer, something like this: require "#{Rails.root}/lib/orm/couchrestmodel"

Now your application is ready to use Devise with CouchDB =)

Devise will use this ORM to create the properties into the documents and views for the autheticable models (including authentication keys)

## TO DO

Create Tests
Maybe convert this ORM to a plugin
Make some refactoring

## Thanks

Special thanks to:
Tapajós [http://twitter.com/tapajos]
Sylvestre Mergulhão [http://twitter.com/smergulhao]



