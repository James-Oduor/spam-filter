# Spam-Filter App
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css" integrity="sha512-5Hs3dF2AEPkpNAR7UiOHba+lRSJNeM2ECkwxUIxC1Q/FLycGTbNapWXB4tP889k5T5Ju8fs4b1P5z/iB4nMfSQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />

This project is a simple web application that uses regular expressions to detect spam messages. Users can input a message in the interface, and the app will analyze it against predefined spam patterns. 


![image](https://github.com/user-attachments/assets/071f91c8-5736-477e-8d0c-c571187f1a63)

---

##<i class="fa-solid fa-diagram-project"></i> Features

- **Interactive User Interface:** Input a message and check its spam status.
- **Customizable Spam Rules:** Uses regular expressions to identify spam messages based on common patterns.
- **Responsive Design:** Styled using CSS for a clean, user-friendly experience.

---

## Project Structure

- **HTML:** Provides the structure of the application.
- **CSS:** Adds styling and responsiveness to the user interface.
- **JavaScript:** Implements the logic for checking messages against spam rules.

---

## Demo

### How It Works
1. Enter a phrase in the input area.
2. Click the "Check message" button.
3. The app will analyze the input and display a result indicating whether it's spam.



---

## Regular Expressions Used

The app uses the following regex patterns to identify potential spam:

- **Help Request Spam:** `/please help|assist me/i`
- **Monetary Amounts Spam:** `/[0-9]+\s*(?:hundred|thousand|million|billion)?\s+dollars/i`
- **Free Money Spam:** `/(?:^|\s)fr[e3][e3] m[o0]n[e3]y(?:$|\s)/i`
- **Stock Alerts Spam:** `/(?:^|\s)[s5][t7][o0][c{[(]k [a@4]l[e3]r[t7](?:$|\s)/i`
- **Generic Greetings Spam:** `/(?:^|\s)d[e3][a@4]r fr[i1|][e3]nd(?:$|\s)/i`

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
