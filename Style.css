const responses = {
  "admission": "Our college admission opens every June. Visit the admin office or our website.",
  "courses": "We offer B.Tech, B.Sc, B.Com, and MBA programs.",
  "hostel": "Yes, we have separate hostels for boys and girls with good facilities.",
  "library": "The library is open from 8 AM to 8 PM on all working days.",
  "placement": "Top companies visit our campus for placements every year.",
};

function sendMessage() {
  let input = document.getElementById("user-input").value.toLowerCase();
  let chatBox = document.getElementById("chat-box");

  let userDiv = document.createElement("div");
  userDiv.textContent = "You: " + input;
  chatBox.appendChild(userDiv);

  let reply = "Sorry, I don't understand. Please contact the admin office.";
  for (let key in responses) {
    if (input.includes(key)) {
      reply = responses[key];
      break;
    }
  }

  let botDiv = document.createElement("div");
  botDiv.textContent = "Bot: " + reply;
  chatBox.appendChild(botDiv);

  document.getElementById("user-input").value = "";
  chatBox.scrollTop = chatBox.scrollHeight;
}