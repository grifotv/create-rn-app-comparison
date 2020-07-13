# Comparison of ways of creating a React Native app

## Core requirements 
- RN V0.63
- TS support
- Bare workflow
- w/ Expo unimodules

## Variants
- [x] myapp--npx-rn--ts-template (`$ npx react-native init MyApp --template react-native-template-typescript`)
	- [x] RN V0.63
	- [x] TS support
	- [x] Bare workflow
	- [ ] w/ Expo unimodules

- [x] myapp--rn--ts-template (`$ react-native init MyApp --template react-native-template-typescript`)
	- [x] RN V0.63
	- [x] TS support
	- [x] Bare workflow
	- [ ] w/ Expo unimodules

- [x] myapp--npx-crnapp--no-template (`$ npx create-react-native-app MyApp`)
	- [ ] RN V0.63
	- [ ] TS support
	- [x] Bare workflow
	- [x] w/ Expo unimodules

- [x] myapp--npx-crnapp--ts-template (`$ npx create-react-native-app MyApp -t with-typescript`)
	- [ ] RN V0.63
	- [x] TS support
	- [ ] Bare workflow
	- [x] w/ Expo unimodules

- [x] myapp--expo--ts-template (`$ expo init MyApp`, pick "Bare workflow > minimal (TypeScript)")
	- [ ] RN V0.63
	- [x] TS support
	- [x] Bare workflow
	- [x] w/ Expo unimodules
