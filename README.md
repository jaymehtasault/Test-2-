# Test-2-
# DiscussionBoard-Likes

This project is an enhanced version of Lab 1. It includes:

-  User registration and login
-  Password strength indicator
-  Show/hide password toggle
-  Discussion board with multiple posts
-  Like/Dislike voting system with unlimited clicks


//used chat gpt for if code
    password.oninput = function () {
      const val = password.value;
      if (val.length < 6) {
        strengthMsg.textContent = "Weak";
        strengthMsg.style.color = "red";
// used chatgpt for append child code
         voteContainer.appendChild(likeLabel);
      voteContainer.appendChild(countDisplay);
      voteContainer.appendChild(dislikeLabel);
