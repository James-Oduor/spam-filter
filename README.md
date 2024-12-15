# Spam-Filter App



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
