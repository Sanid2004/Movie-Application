The SRS document for my project https://docs.google.com/document/d/e/2PACX-1vREgC6sN5qAuPQDFaIH-A4EJCj6QKqVDfrhxSK6tzKMfUUzipRve1sSV4DuNAIjwg/pub

Main Functionalities:
• Role based access control for Registered , Unregistered and Admin users. 
• Password was encrypted using BEncypt Password Encoder and then stored in database (MySQL).
• JWT Authentication on API's pertaining to registered users.
• Use of OMDB Api for fetching the information for a particular movie.
• Payment Integration using Razorpay
• Created Restful API’s for fetching data from local database (CRUD Operations). All API’s were tested on
Postman.
• The registered users can change their profile. They can give ratings , comments and add movies to their bucket
list.
• The unregistered users can only view details of a particular movie . They can read comments provided by the
registered users.
• Our local database consisted of more than 5000 movies.
• Was deployed using AWS using BeanStalk.
• Use of Axios for server integration via ReactJS.
