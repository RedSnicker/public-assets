This is the UI specifications/style that redsnicker uses in his websites.

## Colors

**BG**: #000
**BG1**: #0b0b0b
**BG2**: #141414
**BG3**: #fff

**BG1-HOVER**: #292929
**BG2-HOVER**: #242424
**BG3-HOVER**: #fff 

**TEXT1**: #f4f5f9
**TEXT2**: #c9cdca

# Components

### Buttons
**Border-Radius**: 999px+ (Just have to be pill shaped)
**On Hover**: 0.95 Scale, 0.3 seconds
### Text
**Font**: **Plus Jakarta Sans** and **Sora**, Latin and Extra weight variations.
**Font Weight**: 300+
### Icons
Most Icons used in snickerion come from Lucide React.
They have to be light, non-solid very thin icons. Sometimes animated, sometimes not animated
### Navbars
This usually differs project to project.
But usually its a decently small, pill shaped circle at the top of the screen. <img width="357" height="56" alt="image" src="https://github.com/user-attachments/assets/62419c0a-31c7-43aa-95e7-00d4ebb4d57e" />

It uses BG1,BG1-HOVER and TEXT1 For the colors. 

# Animation
The rule to animations in snickerion is that it always has to be unique. transition from page to page? clicking a wind button? They all have to have custom animations.

Transition duration in snickerion ranges from 0.3-1 second. biased towards 0.3 to improve UX.

# Requirements
All snickerion projects use three libraries. Tailwindcss, Framer Motion & Lucide react.
Always use these. Dont manually write css (Unless you really have to) and rely on tailwind css instead.

Use framer motion for Animations.

and icons is lucide react. it should be pretty obvious from now.
Also note. basically like 80% of components in snickerion are just pills. spam pills and motion divs cuz they're cool😎
