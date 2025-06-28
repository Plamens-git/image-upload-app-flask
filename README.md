This Flask web application was developed as part of the Public Cloud Group (PCG) Penetration Testing Squad application challenge.

The app allows users to upload and delete image files through a simple HTML interface. Access to the application is restricted by IP whitelisting, allowing only the PCG VPN IP address (`20.218.226.24`) to access the interface, as specified in the challenge requirements.

To run the application locally:
1. Install Flask using `pip install Flask`
2. Run the app with `python app.py`
3. Open `http://localhost:5001/` in your browser

Note: The `uploads/` folder is used to store uploaded images but is excluded from Git version control via `.gitignore`. For local testing, the IP restriction can be temporarily disabled by commenting out the relevant lines in `app.py`.

This project was created by Plamen Gospodinov as part of the application process for the Penetration Testing Working Student role at PCG.
