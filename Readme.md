Site API Key
============

- Create a module that serves the following purpose:
 - Add a field to site information available at admin/config/system/site-information named Api Key.
 - Change the text that says Save Configuration to Submit.
 - If a user tries to browse http://localhost/node/<nid>/<api_key>, 
   - Page should say access denied if the api_key doesn’t match the value under the site-information.
    - If it matches, it should render the node object as JSON.
