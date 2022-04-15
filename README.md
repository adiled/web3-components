The ever-growing p2p ecosystem around blockchain-based protocols leaves the challenge of standardization open. The UI landscape is similarly in disarray. It may be argued that that's a good thing given "decentralization", however, a case can be made for robust UI primitives for needs such as addressing and perhaps more that establish with time.

## Scope

`web3-elements` is to be designed around specs. Core elements are to be distinctly atomic and implemented judicially. Compositions from these elements may be created outside the core, yet within the package, however only such composite elements that are expected to work similarly across web3 UIs.

To be inline with the scope, core elements have to be as lightweight as possible. Present consideration for building is through web components, however controversial, that is the only balanced solution. Libraries that are evaluated include SvelteJS, Lit, and SolidJS for compilation to web components. SolidJS is both impressive in its proposition, and a winner in benchmarks, and might be the choice.

## How this is useful

Primitive core and composite elements serve just like expansive DOM elements of HTML5. As more traction goes towards UI libraries and their implementations in frontend frameworks on the view layer, web3 elements may be utilized. This may be hard to push to larger adoption due to the smoke that surrounds "web components", but will remain an option for those realizing that it opens up development web3-native frontends by anyone without prejudice founded in tribal nature of early web3.

## Structure

`web3-elements` is a scoped monorepo packaging: primitive elements as web components compiled with SolidJS, while wrapped and higher order components built in react and vue.