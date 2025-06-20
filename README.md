target.onclick = null;
target.onclick = function () {
  hits++;
  updateStats();
  target.style.display = 'none';
  target.onclick = null; // prevent multiple hits
};
