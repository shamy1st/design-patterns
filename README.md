# Design Patterns

**Design Pattern** elegant solution to repeating problem. / Design reusable, extensible object-oriented software.
Book: [Design Patterns: Elements of Reusable Object-Oriented Software by GoF](https://en.wikipedia.org/wiki/Design_Patterns)
***
**Creational** (way to create objects)
* [Factory Method](https://github.com/shamy1st/design-pattern-factory) create objects without specifying the class of the object. / Shape(Circle, ...), ShapeFactory
* [Abstract Factory]()
* [Builder]()
* [Prototype]()
* [Singleton]()
* [Object Pool]()

**Structural** (relationship between objects)
* [Adapter](https://github.com/shamy1st/design-pattern-adapter) convert interface of a class into another interface that clients expect. / Image, external Caramel filter
* [Bridge](https://github.com/shamy1st/design-pattern-bridge) connect two independent hierarchies, build a simple flexible hierarchy. / RemoteControl, Sony, Samsung
* [Composite](https://github.com/shamy1st/design-pattern-composite) group of objects treated the same way as a single instance. / Shape(Circle, Square), Group
* [Decorator](https://github.com/shamy1st/design-pattern-decorator) add additional behaviour to an object. / CloudStream, (1. encrypt, 2. compress, 3. store)
* [Facade](https://github.com/shamy1st/design-pattern-facade) simple interface to a complex system. / NotificationServer, mobile app users
* [Flyweight](https://github.com/shamy1st/design-pattern-flyweight) object share data as possible with similar objects to minimize memory usage. / Point, map app
* [Proxy](https://github.com/shamy1st/design-pattern-proxy) create a proxy "agent" from a real object. / Library, Ebook

**Behavioural** (interaction between objects)
* [Chain of Responsibility](https://github.com/shamy1st/design-pattern-chain-of-responsibility) build a pipeline of processing objects for a request. / WebServer, handle() HttpRequest
* [Command](https://github.com/shamy1st/design-pattern-command) object used to perform an action at a later time. / Button, click()
* [Interpreter]()
* [Iterator](https://github.com/shamy1st/design-pattern-iterator) iterating over an object without exposing the internal structure. / BrowserHistory, loop through Urls
* [Mediator](https://github.com/shamy1st/design-pattern-mediator) object encapsulates how a set of objects interact. / DialogBox(ListBox, TextBox, Button)
* [Memento](https://github.com/shamy1st/design-pattern-memento) restoring an object to a previous state (undo). / Editor, undo() mechanism
* [Observer](https://github.com/shamy1st/design-pattern-observer) object notify observers when its state changes. / DataSource, Chart, SpreadSheet
* [State](https://github.com/shamy1st/design-pattern-state) object behaviour changes based on its state. / Canvas, current Tool (Brush, Eraser)
* [Strategy](https://github.com/shamy1st/design-pattern-strategy) selecting an algorithm at runtime. / ImageStorage, compress(), apply() filter before store()
* [Template Method](https://github.com/shamy1st/design-pattern-template) define a template for an operation. / TransferMoney, GenerateReport, share task auditTrail
* [Visitor](https://github.com/shamy1st/design-pattern-visitor) add new operation to an object structure without modifying it. / HtmlDocument, HtmlNode, plaintext()
