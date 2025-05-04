# Ai--portfolio---advisor
// script.js function generateIdea() { const input = document.getElementById("skillsInput").value.toLowerCase(); const result = document.getElementById("result");

let idea = "";

if (input.includes("html") && input.includes("css") && input.includes("javascript")) { idea = "Build a personal portfolio website with interactive UI sections, like tabs, sliders, and a project gallery."; } else if (input.includes("bootstrap")) { idea = "Create a responsive landing page for a startup using Bootstrap."; } else if (input.includes("ai")) { idea = "Make a static AI tool UI where user can input a prompt and receive a dummy AI response (simulated)."; } else { idea = "Try learning a new framework like Bootstrap or JavaScript DOM, and build a simple to-do app!"; }

result.innerText = idea; }

