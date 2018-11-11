# MatSearchable
[https://github.com/bl4y/mat-searchable](https://github.com/bl4y/mat-searchable)

## What is MatSearchable?
*MatSearchable* is a lightweight library for adding filtering and searching capabilities to the [MatSelect](https://material.angular.io/components/select/overview) component.

## ..yet another searching library?
Well, almost!

The most important trait of *MatSearchable* (compared to other extension libraries) is that it requires **no refactorization** of your current MatSelect implementation.

*MatSearchable* does not manipulate your original input data or require you to mess up your clean code. It leverages advanced DOM manipulation techniques, reaching identical performance to the built-in core directives, like **ngFor**.

**Try it**, if you don't believe me:

## How to use it?
#### Install the package:
```sh
npm install @bl4y/mat-searchable
```

#### Reference the module in your `app.module.ts`:
```typescript
import { MatSearchableModule } from '@bl4y/mat-searchable';

@NgModule({
  imports: [
    BrowserModule,
    BrowserAnimationsModule,

    MatSearchableModule //! <<<<<<<<<
  ]
})
export class AppModule { }
```

#### Add the neccessary directives and components to your current logic:
![Diff](docs/diff.png)

Pretty awesome, huh?

## Contributions
Contributions are always welcome, please open an issue or a pull request!

## Support me!
If you feel like this library supported you and your project, you can contribute to it's maintenance by [buying me a cup of coffee](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=D8FHCS57JAD3N) :)