

function replaceWords(replacements) {
  const elements = document.querySelectorAll('*');
  elements.forEach(element => {
    let textContent = element.textContent;
    for (const [oldWord, newWord] of replacements) {
      const regex = new RegExp(`\\b${oldWord}\\b`, 'g');
      textContent = textContent.replace(regex, newWord);
    }
    element.textContent = textContent;
  });
}




const replacements = [
  ['the', 'the ol'],
  ['food', 'grub'],
  ['yes', 'aye'],
  ['hi', 'ahoy'],
  ['hello', 'ahoy'],
  ['stop', 'heave to!'],
  ['toilet', 'head'],
  ['crew', 'hands'],
  ['worker', 'hand'],
  ['workers', 'hands'],
  ['helper', 'hand'],
  ['helpers', 'hand'],
  ['friend', 'matey'],
  ['child', 'lad'],
  ['kid', 'lad'],
  ['rebellion', 'mutiny'],
  ['my', 'me'],
  ['revolution', 'mutiny!'],
  ['steal', 'plunder'],
  ['prank', 'rig'],
  ['you', 'ye'],
  ['wow', 'blimey!'],
  ['woah', 'blimey!'],
  ['this', 'this'],
  ['woah', 'blimey!'],
  ['this', 'this'],
  ['have', 'ave'],
  ['woah', 'blimey!'],
  ['there', 'thar'],
  ['should', 'best'],
  ['room', 'cabin'],
  ['to', 't'],
  ['everything', 'everythin!'],
  ['woah', 'blimey!'],
  ['this', 'this'],
  ['woah', 'blimey!'],
  ['this', 'this'],
  ['have', 'ave'],
  ['and', 'n'],
  ['your', 'yer'],

  // Add more replacements here
];

replaceWords(replacements);
