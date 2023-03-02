## Perspective API Connector:

This module will help to identify whether the given input has toxic content or not. Perspective API services uses trained machine learning models to idendify the toxic messages.

### Use case scenario :

Publishers, platforms, and individuals can use Perspective to power a variety of different use cases, in comment sections, forums, or any text-based conversations. Developers integrate and customize Perspective for many different audiences.

### Dependencies:

• Requires Mendix Modeler 8.18.23 or higher.

• Access to Perspective API services in Google Cloud Platform.

• API Key from Perspective API.

For more info : 
#### https://developers.perspectiveapi.com/s/docs-get-started?language=en_US

### Configuration:

1. Create a project in Google Cloud platform.
2. Enable Perspective API services to get an API Key.
3. Configure the API Key in CONST_APIKey.
4. Add ACT_GenerateToxicityScore microflows to your flow.
5. In ACT_GenerateToxicityScore microflow, you need to update the Body string variable with Input text and Source language as a String value.

For detailed information, you can read my blog by clicking on the link below.

#### https://medium.com/mendix/predict-my-message-stop-hateful-comments-online-with-google-perspective-api-165ad7a0eda2.

That's it. Now you can be able to find toxic messages sent by users. 
