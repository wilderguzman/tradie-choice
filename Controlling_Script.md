> # home.php Controller #
https://test.tradiechoice.com/index.php
-> Home page<br />
->/app/controllers/home.php (  function index()   )  --------> Controller<br />
->/app/views/home.php ---------->view

---


> # project.php Controller #
https://test.tradiechoice.com/index.php/project/create_custom
->buyer post a new project<br />
->/app/controllers/project.php (  function create\_custom()  )  --------> Controller<br />
->/app/views/project/createProjectCustom.php -------------->view

---

https://test.tradiechoice.com/index.php/project/create
-> client  post a new project<br />
->/app/controllers/project.php (  function create()  )  --------> Controller<br />
->/app/views /project/ createProject.php --------->view

---

https://test.tradiechoice.com/index.php/project/view/130  (project\_id )
-> view a project<br />
->/app/controllers/project.php (  function view()  )  --------> Controller<br />
->/app/views/ project/ viewProject.php --------->view

---

https://test.tradiechoice.com/index.php/project/category/Plumber  (category name )
-> category page<br />
->/app/controllers/project.php (  function category()  )  --------> Controller<br />
->/app/views/project/listProjects.php --------->view

---

https://test.tradiechoice.com/index.php/project/postBid/130 (project\_id )
->  post a new bid<br />
->/app/controllers/project.php (  function postBid()  )  --------> Controller<br />
->/app/views/project /postBid.php --------->view<br />

---


> # signup.php Controller #
https://test.tradiechoice.com/index.php/signup
-> Signup page<br />
->/app/controllers/signup.php (  function index()   )  --------> Controller<br />
->/app/views/signup/Signup.php ---------->view

---

https://test.tradiechoice.com/index.php/signup/finalstep/activation_key
-> Signup process final step2<br />
->/app/controllers/signup.php (  function finalstep()   )  --------> Controller<br />
->redirect info page ---------->view

---

https://test.tradiechoice.com/index.php/signup/confirm/activation_key
-> Signup process final step for confirm email <br />
->/app/controllers/signup.php (  function confirm()   )  --------> Controller<br />
->redirect info page ---------->view

---

> > # users.php Controller #

https://test.tradiechoice.com/index.php/users
-> User page<br />
->/app/controllers/users.php (  function index()   )  --------> Controller<br />
->/app/views/users/userList\_1.php ---------->view

---


https://test.tradiechoice.com/index.php/users/login
-> Login page<br />
->/app/controllers/users.php (  function login()   )  --------> Controller<br />
->/app/views/users/loginUsers.php ---------->view

---


https://test.tradiechoice.com/index.php/users/forgotPassword
-> Forgot Password page<br />
->/app/controllers/users.php (  function forgotPassword()   )  --------> Controller<br />
->/app/views/users/forgotPassword.php ---------->view

---


https://test.tradiechoice.com/index.php/users/logout
-> Logout<br />
->/app/controllers/users.php (  function logout()   )  --------> Controller<br />
->redirect info page ---------->view

---


> # projects.php Controller #

https://test.tradiechoice.com/index.php/projects/index
-> search by project page<br />
->/app/controllers/projects.php (  function index()   )  --------> Controller<br />
->/app/views/project/search.php ---------->view

---


> # buyer.php Controller #

https://test.tradiechoice.com/index.php/buyer/getBuyersreview
-> Loads the top buyers<br />
->/app/controllers/buyer.php (  function getBuyersreview()   )  --------> Controller<br />
->/app/views/buyer/topBuyer.php ---------->view

---


https://test.tradiechoice.com/index.php/buyer/signUp
-> Loads the signup page<br />
->/app/controllers/buyer.php ( function signUp() )  --------> Controller<br />
->/app/views/buyer/buyerSignup.php ---------->view

---


https://test.tradiechoice.com/index.php/buyer/resendActLink
-> Resend activation link when users requested<br />
->/app/controllers/buyer.php ( function signUp() )  --------> Controller<br />
->/app/views/buyer/buyerSignup.php ---------->view

---


https://test.tradiechoice.com/index.php/buyer/confirm/activation_key
-> Confirm signup process by activating key <br />
->/app/controllers/buyer.php ( function signUp() )  --------> Controller<br />
->/app/views/buyer/buyerConfirm.php ---------->view

---


https://test.tradiechoice.com/index.php/buyer/editProfile/buyer_id
-> editProfile for both buyer and programmer for edit his profile <br />
->/app/controllers/buyer.php ( function signUp() )  --------> Controller<br />
->/app/views/buyer/editBuyerProfile.php ---------->view

---


https://test.tradiechoice.com/index.php/buyer/viewMyProjects/buyer_id
-> View projects posted by a buyer <br />
->/app/controllers/buyer.php ( function signUp() )  --------> Controller<br />
->/app/views/buyer/myProjects.php ---------->view

---


https://test.tradiechoice.com/index.php/buyer/refundMoney/project_id
-> Refund money to programmer  <br />
->/app/controllers/buyer.php ( function signUp() )  --------> Controller<br />
->Redirect to /app/views/buyer/viewtransaction.php ---------->view

---


https://test.tradiechoice.com/index.php/buyer/viewProfile/buyer_id
-> View buyer's profile  <br />
->/app/controllers/buyer.php ( function signUp() )  --------> Controller<br />
->/app/views/buyer/viewProfile.php ---------->view

---


https://test.tradiechoice.com/index.php/buyer/reviewProgrammer/programmer_id
-> Review Corresponding Programmers <br />
->/app/controllers/buyer.php ( function signUp() )  --------> Controller<br />
->/app/views/buyer/reviewProgrammer.php ---------->view

---


https://test.tradiechoice.com/index.php/buyer/review/buyer_id
-> Lists review of a provider <br />
->/app/controllers/buyer.php ( function signUp() )  --------> Controller<br />
->/app/views/buyer/reviews.php ---------->view

---


> # account.php Controller #

https://test.tradiechoice.com/index.php/account/edit
-> Loads the account page and edit the profile<br />
->/app/controllers/account.php (  function edit()   )  --------> Controller<br />
->/app/views/account/edit.php ---------->view

---


https://test.tradiechoice.com/index.php/account/viewMail
-> Loads the viewmail page with inbox & outbox mail list <br />
->/app/controllers/account.php (  function edit()   )  --------> Controller<br />
->/app/views/account/mymail.php ---------->view

---


https://test.tradiechoice.com/index.php/account/deleteMail/mail_id
->Delete email <br />
->/app/controllers/account.php (  function edit()   )  --------> Controller<br />
->/app/views/account/mymail.php ---------->view (delete with ajax call)

---


https://test.tradiechoice.com/index.php/account/readMail/mail_id
->Read the corresponding email <br />
->/app/controllers/account.php (  function edit()   )  --------> Controller<br />
->/app/views/account/mymail.php ---------->view (read with ajax call)

---


https://test.tradiechoice.com/index.php/account/reviews
->Loads the review list <br />
->/app/controllers/account.php (  function edit()   )  --------> Controller<br />
->/app/views/account/reviews.php ---------->view

---



https://test.tradiechoice.com/index.php/account/favoriteUsers
->Loads the favorite user list <br />
->/app/controllers/account.php (  function edit()   )  --------> Controller<br />
->/app/views/account/favorite.php ---------->view

---


https://test.tradiechoice.com/index.php/account/blockedUsers
->Loads the blocked user list <br />
->/app/controllers/account.php (  function edit()   )  --------> Controller<br />
->/app/views/account/blocked.php ---------->view

---


https://test.tradiechoice.com/index.php/account/notification
->Loads email notification settings <br />
->/app/controllers/account.php (  function edit()   )  --------> Controller<br />
->/app/views/account/notification.php ---------->view

---
