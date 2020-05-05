# NuxtDjango
Test Repository to deal with connecting Nuxt as the default frontend of Django. Focus on authentication and database updates. 

Goal:
1. Django REST API Server that can serve one table.
2. The same Django Server will also serve its authentication via REST API.
3. A Nuxt Frontend, that authenticates the user against the Django authentication API.
4. The same nuxt frontend should show a logged-in user the table served via the REST API.
4.1. Optional: Make the same table editable and send the results back to the django REST API.

Sources:
1. Nuxt and django tutorial: https://www.digitalocean.com/community/tutorials/how-to-build-a-universal-application-with-nuxt-js-and-django. Unfortunately, they do not explain how to use a table here. 
2. This is the general documentation for api-authentication with django: https://www.django-rest-framework.org/api-guide/authentication/. This is a user based example that authenticates nuxt and django via the third party app djoser: https://github.com/charly24/nuxt-django. Having this independent of djoser would be better. Please check if this is feasible.
3. This is a general approach via JWT: https://www.digitalocean.com/community/tutorials/implementing-authentication-in-nuxtjs-app JWT should also be the general approach for our solution. This solution also has specific code for implementing authentication via nuxt and djoser: https://github.com/charly24/nuxt-django.
