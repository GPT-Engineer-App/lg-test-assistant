# lg-test-assistant

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LG Aptitude Test</title>
<style>
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background-color: #f9f9f9;
        margin: 0;
        padding: 0;
    }

   .container {
    width: 100%;
    margin: 20px auto;
    padding: 20px;
    background: linear-gradient(135deg, #c80541, #ff5733); /* Gradient from LG Red to another color */
    color: #fff; /* White text color */
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    animation: fadeIn 1s;
}


@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(-20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}


   h1 {
    text-align: center;
    color: #fff; /* White text color */
    font-size: 36px;
    margin-bottom: 20px;
}

 .info {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
  }

  .info-item {
    flex: 0 0 48%;
    padding: 10px;
   
  }

  .experience {
    flex: 0 0 48%;
    padding: 10px;
    
  }

  .experience p {
    margin-bottom: 5px;
  }
    .question {
        margin-bottom: 30px;
    }

   .question-text {
    font-weight: bold;
    color: #fff; /* White text color */
    font-size: 18px;
}

.option {
    padding: 8px 15px;
    margin-bottom: 5px;
    background-color: #ffffff20; /* Semi-transparent white background */
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
    display: flex;
    align-items: center;
}


    .option input[type="radio"] {
        margin-right: 10px;
    }

  .option:hover {
    background-color: rgba(255, 128, 128, 0.8); /* Light red with reduced opacity */
}

.next-button {
    display: block;
    margin: 20px auto 0;
    padding: 12px 24px;
    background-color: #ff0055; /* Lighter red to complement the gradient */
    color: #fff; /* White text color */
    border: none;
    border-radius: 25px;
    cursor: pointer;
    transition: background-color 0.3s;
    font-size: 16px;
    text-transform: uppercase;
    font-weight: bold;
    overflow: hidden;
    position: relative;
}

.next-button:hover {
    background-color: #c80541; /* Darker red on hover */
}



.next-button:hover::before {
    transform: translate(-50%, -50%) scale(1);
    opacity: 1;
}


</style>
</head>
<body>

   <div class="container">
  <h1><span class="highlight">TEST: Process Loss Improvement(PLI)</span></h1>  <div class="info">
    <div class="info-item">
      <p><strong>Name:</strong> <span class="value">Not Provided</span></p>
      <p><strong>Department:</strong> <span class="value">Not Provided</span></p>
      <p><strong>Total Experience:</strong> <span class="value">Not Provided</span></p>
    </div>
    <div class="experience">
      <p><strong>Time:</strong> <span class="value">15 Mins</span></p>
      <p><strong>Marks:</strong> <span class="value">10</span></p>
    </div>
  </div>
  <hr>
    
    <div class="question">
        <p class="question-text">1) Four steps for field improvement</p>
        <div class="options">
            <label class="option"><input type="radio" name="field_improvement" value="option1">   A) FMS Setup -> Improvement of JIG/LCA -> Efficiency Step -> Improvement of JIG/LCA Improvement accompanied by Design
<br></label>
            <label class="option"><input type="radio" name="q1" value="2"> B) Efficiency Step FMS Setup -> Improvement of JIG/LCA FMS Setup -> Improvement accompanied by Design -> FMS Setup
<br></label>
            <label class="option"><input type="radio" name="q1" value="3">C) Improvement accompanied by design -> Efficiency Step -> FMS Setup -> Improvement of JIG/LCA
<br></label>
            <label class="option"><input type="radio" name="q1" value="4">  D) Improvement of JIG/LCA -> FMS Setup -> Efficiency Step -> Improvement accompanied by design</label>
        </div>
    </div>
    <button class="next-button">Next</button>
</body>
</html>
 here is the code increse the size of radio button


## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/lg-test-assistant.git
cd lg-test-assistant
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
