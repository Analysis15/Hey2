intro
function changeButtonText() {

  const noButton = document.getElementById('noButton');

  noButton.innerHTML = 'Yes';

  noButton.onclick = function() {

    alert("Yay! Let's go!");

  };

}
