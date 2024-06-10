# Dynamic-Portfolio
Dynamic Portfolio website which consists the overview of my technical journey as well as my performance in my graduation degree expressing through this website.

# How to connect your responsive form to the excel file for data exchange and collection.
 There are several codes which are required to connect the same mentioned below:-


 
 <script>
    const scriptURL = '<URL>'
    const form = document.forms['submit-to-google-sheet']
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => console.log('Success!', response))
        .catch(error => console.error('Error!', error.message))
    })
  </script>
# Deployment
Deployed using netlify  https://sur21portfolio.netlify.app/

# Languages Used
HTML< br / >
CSS< br / >
JAVASCRIPT
