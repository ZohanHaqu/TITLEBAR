import { Titlebar } from '@6c65726f79/custom-titlebar';

let titlebar;
const menu = [
  {
    label: 'File',
    submenu: [
      {
        label: 'Checkbox',
        type: 'checkbox',
        id: 'checkbox'
      },
      {
        label: 'Checked state',
        click: () => {
          const item = titlebar.getMenuItemById('checkbox');
          alert(item?.checked ? 'Checked' : 'Unchecked');
        }
      }
    ]
  }
];

function createTitlebar() {
  titlebar = new Titlebar({
    backgroundUnfocusEffect: false,
    windowControlsOverlay: true,
    backgroundColor: '#2975ff',
    menu
  });
}

window.addEventListener('load', () => {
  // Use the titlebar only in standalone mode
  if (navigator.standalone || window.matchMedia('(display-mode: standalone)').matches) {
    createTitlebar();
  }

  window.matchMedia('(display-mode: standalone)').onchange = (e) => {
    e.matches ? createTitlebar() : titlebar.dispose();
  };
});
