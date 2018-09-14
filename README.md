# Framer X

## 欢迎

感谢加入测试版。这份文档在正式版出来之前仍然处于撰写中的状态，欢迎提反馈意见，也欢迎直接在 Github 修改错误之处。

### 最好的开始方式

* 阅读[如何思考 Framer X](https://framer.gitbook.io/framer/#how-to-think-about-framer-x) 和下面的“支持的设计流程”
* 阅读[测试版页面](introduction/beta/) _**提示**: 代码部分许多内容仍在频繁更新中 \(code functions, state\)，最好随时查阅。_
* 你可以自己先探索画布、自动布局、样式、Stacks、设计组件、页面流和滚动内容，从设计商店中安装一些简单的 React 组件，也可以尝试在属性面板中[自定义属性](components/#adding-framer-interface-for-props) 。


## 如何思考 Framer X

Framer X 和其它设计工具完全不一样，我们的目的是**混合画布和代码**，或者说**混合设计和开发**，这是一种全新的、高效自然的设计数字化产品的方式。

Framer X 更像是 [Unity](https://unity3d.com/unity/editor) ，而不是 photoshop。它是一个**设计师的** [**IDE**](https://en.wikipedia.org/wiki/Integrated_development_environment)。Framer X 可以做很多不同的事情，从线框图到视觉设计，从页面流到设计系统，再到代码构建的交互组件，我们希望每一个设计师能够根据自己的需求或技能来使用。

>Framer X is both the **most easy and most advanced** design tool. We think a subset of more advanced users will build components for everyone else, so the majority of users won’t write code, but visually compose interfaces with components built by others through the store. But if you enjoy writing code, Framer X will be the best environment to do so and we encourage everyone to explore it.

The idea behind Framer X is **not to generate code for you**, but instead to use the code you \(or someone else\) wrote. Auto generated code almost never ends up in production, so it's better to have a tool use the code that is being used. If you already have React components built, they should work in Framer X with minimal effort. That said, _everything_ you draw in Framer is a React component and exportable to `jsx`, `html` or static assets if you need it.

## Supported Design Workflows

The goal of Framer X is to support many types of workflows, and with that many types of users at different skill levels, but to never hold you back and even encourage you to explore more.

The list below is an example of parts of Framer X you would need for different design tasks. Make sure to check our [beta feature list](introduction/beta/#beta-features) to make sure what is available today.

**A. Wire-framing** – quickly visualize an interactive idea, layout, user flow and information architecture.

* **Interface:** login, signup, canvas, properties, tools, layers, components, store.
* **Canvas:** navigation, selection, editing.
* **Layout:** \(auto\) hierarchy, \(auto\) positioning, frames, images, text, stacks.

_No previous skills required._

**B. Visual Design** – explore styling options for layouts, create icons and artwork and produce high res assets for production with pixel level control.

* **Drawing:** shapes, path editing, styling, grouping, boolean operations.
* **Import / Export:** paste, Sketch paste, image exporting, SVG exporting, code export.

_Helpful to have: some experience with drawing tools, computer graphics._

**C. Interactive** – quickly turn visual parts into a prototype with navigation, different screens, advanced scrolling and some interactive components. All without code.

* **Preview:** window, frame selection, device, presentation mode, mobile preview, remote preview, inspector, print.
* **Interactive:** link, scroll, page.
* **Design Components:** panel, organization, search, master, instance, overrides, nesting, use from code.
* **Store:** browse, search, install, update, private company store.
* **Sharing:** cloud, web project.

_Helpful to know: HTML, CSS, web publishing._

**D. Expert interactive** – create real products, invent your own interactions with state, data, physics, user input and combine with any other JavaScript out there.

* **Code Components:** creation, editing, interface props, canvas children.
* **Code Functions:** creation, editing, state.
* **Code Library:** animation, interpolation, events, gestures, components.

_Helpful to know: JavaScript, React, motion graphics._

**E. Design Infra** – build and manage from components to entire design systems for teams, scale them to large organizations, integrate with production.

* **Packages:** publish, update, versioning, dependencies.

_Helpful to know: NPM, Yarn._

![](.gitbook/assets/framer%20%281%29.png)
