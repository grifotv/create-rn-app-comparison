# Comparison of ways of creating a React Native app

## Core requirements 
- RN V0.63
- TS support
- Bare workflow
- w/ Expo unimodules

## Variants
- [x] [myapp--npx-rn--ts-template](https://github.com/grifotv/create-rn-app-comparison/tree/myapp--npx-rn--ts-template/MyApp) (`$ npx react-native init MyApp --template react-native-template-typescript`)
	- [x] RN V0.63
	- [x] TS support
	- [x] Bare workflow
	- [ ] w/ Expo unimodules

- [x] [myapp--npx-crnapp--no-template](https://github.com/grifotv/create-rn-app-comparison/tree/myapp--npx-crnapp--no-template/MyApp) (`$ npx create-react-native-app MyApp`)
	- [ ] RN V0.63
	- [ ] TS support
	- [x] Bare workflow
	- [x] w/ Expo unimodules

- [x] [myapp--npx-crnapp--ts-template](https://github.com/grifotv/create-rn-app-comparison/tree/myapp--npx-crnapp--ts-template/MyApp) (`$ npx create-react-native-app MyApp -t with-typescript`)
	- [ ] RN V0.63
	- [x] TS support
	- [ ] Bare workflow
	- [x] w/ Expo unimodules

- [x] [myapp--expo--ts-template](https://github.com/grifotv/create-rn-app-comparison/tree/myapp--expo--ts-template/MyApp) (`$ expo init MyApp`, pick "Bare workflow > minimal (TypeScript)")
	- [ ] RN V0.63
	- [x] TS support
	- [x] Bare workflow
	- [x] w/ Expo unimodules
