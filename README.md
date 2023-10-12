# How to integrate the Figma design library to Storybook

GIT: *https://github.com/abhishekchaturvedi-07/figma-storybook-integration*  
1- You need a Figma Frame / Component Link  
2- You need a component where you can set up your required parameters  
MAKE SURE ABOUT THE DESIGN TYPE

```
parameters: {
        design: {
            type: 'figspec',
            url: 'https://www.figma.com/file/QqXWSdBmrFTj2Hd0bojWleYv/Figma-Embed-Example?type=design&node-id=0-2&mode=design&t=gIfsIxAsTnLhuW8A-4',
            accessToken: "<CAN BE GENERATED FROM HERE>",
        }
    }
```

3- You need to generate the token from figma developer account!
