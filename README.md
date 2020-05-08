## PITCH

### DESCRIPTION

The Pitch application allows users to submit their one minute pitches and other users will vote on them and leave comments to give their feedback. The pitches are organized by category. You can visit the live site on

### AUTHOR

SHEILA EGEIDZA

### FEATURES

As a user you are able to:

1. see all submitted pitches 

2. CReate an account

3. log in

4. Add pitch

5. Upvote or downvote a pitch

6. Comment on a pitch

7. See comments posted on each individual pitch

8. Edit your profile i.e will be able to add a short bio about yourself and a profile picture

### SPECIFICATIONS


  <table>
    <thead>
      <tr>
        <th>Behaviour</th>
        <th>Input</th>
        <th>Output</th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>View product Pitches</td>
            <td>Click on any category</td>
            <td>Taken to clicked category</td>
        </tr>
        <tr>
            <td>"Click on Click Here To Post A Pitch"</td>
            <td>if logged in, display form to add a pitch</td>
            <td>Redirected to the home page</td>
        </tr>
        <tr>
            <td>Click upvote/ downvote button</td>
            <td>Redirects to home page</td>
            <td>Upvote/ downvote count changes</td>
        </tr>
        <tr>
            <td>Click on profile</td>
            <td>Redirects to the profile page</td>
            <td>User adds bio and profile picture </td>
        </tr>
    </tbody>
  </table>

  ### GETTING STARTED

  #### Prerequisites

  - Python3.7
  - Virtual enviroment
  - Pip

  ### Cloning

  - In your terminal:

   <code>git clone https://github.com/mmbukane-shy6/PITCH.git</code>
   <code>cd pitch</code>
   
   ### RUNNING APPLICATION

   * Install virtual environment using <code>$ python3.6 -m venv --without-pip virtual</code>

   * Activate virtual environment using <code>$ </code>source virtual/bin/activate

   * Download pip in our environment using <code> $ curl https://bootstrap.pypa.io/get-pip.py | python</code>

   * Install all the dependencies from the requirements.txt file by running <code>python3.6 pip install -r requirements.txt</code>

   * Create a <code>start.sh</code> file in the root of the folder and add the following code:
   
    export MAIL_USERNAME=<your-email-address>

    export MAIL_PASSWORD=<your-email-password>

    export SECRET_KEY=<your-secret-key>
    

    * Edit the configuration instance in <code>manage.py<code> by commenting on production instance and uncommenting development instance

    * To run the application, in your terminal:

     - chmod a+x start.sh

    - ./start.sh

    * To tun the tests for the class file:

      $ python3.6 manage.py server

    ### TECHNOLOGIES USED

    * Python3.7
    * Flask
    * HTML
    * Bootsrap

    This application is developed using Python3.6,Flask,HTML and Bootsrap

### CONTACT INFORMATION

Email: sheilaegeidza@gmail.com

### LICENCE
MIT License: <code>LICENSE MIT</code>

Copyright (c) 2020 Sheila Egeidza





