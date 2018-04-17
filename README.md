# fema-mapper
A simple, full stack web application which helps in visualizing the FEMA disasters dataset.
View at http://django-env.bzjvgpxk2x.us-west-2.elasticbeanstalk.com/

To run locally (you don't need to, but for debugging purposes):

source djangoEnv/bin/activate

python3 mapper/manage.py runserver

All dependencies are already installed in the virtual environment, so the above 2 steps should be sufficient.

Remember, to view Hawaii, you might need to pan in the map. Some disasters like typhoons
are actually exclusive to that region, and can only be viewed by panning over to that region.

The choice to have tornados and volcanos selected by default is completely arbitrary.
