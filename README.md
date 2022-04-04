# Custom xfce panel theme installer
- Note: (All the theme are made by https://github.com/mehedirm6244)

#### 1. Copy gtk.css file to ~/.config/gtk-3.0/
`cp gtk.css ~/.config/gtk-3.0/`

#### 2. Copy xfce4-panel.xml to xfce4 config folder 
1. `killall xfconfd`

2. `cp my-cfg-0.xml ~/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-panel.xml`

3. `xfce4-panel -r`

#### And BOOM! 🥳 your xfce looks so much better isn't it? :D