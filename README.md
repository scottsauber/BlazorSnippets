# Blazor Snippets for VS Code

Blazor Snippets for VS Code provides common snippets for writing Blazor apps in VS Code and lets you spend less time writing boilerplate and more time writing your app.

> ### Note: All Snippets start with a "b" prefix for discoverability purposes!!!

## Demo

This demo combines multiple snippets together:

1. It uses `bc` to create a blank Blazor Component.
1. `bpara` to create a parameter.
1. `binjhttp` to inject an HttpClient.
1. `boi` to create OnInitializedAsync.
1. `bgja` to make the AJAX call.

![Snippets used together](images/Demo1.gif)

## Blazor Component Snippets

| Snippet        | Purpose                                                    |
| -------------- | ---------------------------------------------------------- |
| `bc`           | Creates a blank Blazor Component.                          |
| `bchttp`       | Creates a Blazor Component with an HTTP call.              |
| `bcchild`      | Creates a Blazor Child Component that accepts a parameter. |
| `bccv`         | Creates a Blazor `<CascadingValue>` Component              |
| `beditform`    | Creates a `<EditForm>` Component                           |
| `bdavalidator` | Creates a `<DataAnnotationsValidator>` Component           |
| `bitext`       | Creates a `<InputText>` Component                          |
| `bitextarea`   | Creates a `<InputTextArea>` Component                      |
| `bicheck`      | Creates a `<InputCheckbox>` Component                      |
| `binumber`     | Creates a `<InputNumber>` Component                        |
| `bidate`       | Creates a `<InputDate>` Component                          |
| `biselect`     | Creates a `<InputSelect>` Component                        |

## Blazor Event Snippets

| Snippet  | Purpose                                                 |
| -------- | ------------------------------------------------------- |
| `boi`    | Creates an `OnInitializedAsync` event.                  |
| `bois`   | Creates an `OnInitialized` event (s for synchronous).   |
| `boar`   | Creates an `OnAfterRenderAsync` event.                  |
| `boars`  | Creates an `OnAfterRender` event (s for synchronous)    |
| `bops`   | Creates an `OnParametersSetAsync` event.                |
| `bopss`  | Creates an `OnParametersSet` event (s for synchronous). |
| `bsr`    | Creates a `ShouldRender` event.                         |
| `bonch`  | Creates an `OnChangeAsync` event.                       |
| `bonchs` | Creates an `OnChange` event (s for synchronous).        |

## Blazor Razor Snippets

| Snippet    | Purpose                                                                                                                  |
| ---------- | ------------------------------------------------------------------------------------------------------------------------ |
| `bfunc`    | Creates a `@functions` block.                                                                                            |
| `bcode`    | Creates a `@code` block.                                                                                                 |
| `bpara`    | Creates a property with a Parameter attribute. Example: `[Parameter] public string Name { get; set; }`                   |
| `bcpara`   | Creates a property with a CascadingParameter attribute. Example: `[CascadingParameter] public string Name { get; set; }` |
| `bpg`      | Creates `@page "/"` with a route.                                                                                        |
| `binj`     | Creates `@inject Type Name` directive.                                                                                   |
| `binjhttp` | Creates `@inject HttpClient Http`.                                                                                       |
| `binjconf` | Creates `@inject IConfiguration Configuration`.                                                                          |
| `binh`     | Creates `@inherits` directive.                                                                                           |
| `bforeach` | Creates `@foreach` directive.                                                                                            |
| `bfor`     | Creates `@for` directive.                                                                                                |
| `bif`      | Creates `@if` directive.                                                                                                 |
| `bife`     | Creates `@if` `@else` directive.                                                                                         |
| `bgja`     | Creates `@await Http.GetFromJsonAsync<string>("api/")`.                                                                  |
| `bprop`    | Creates a property. Example: `public string Name { get; set; }`                                                          |

## Usage

Type part of a snippet, press `tab` and the snippet unfolds. Continue hitting tab for certan snippets that let you jump to the next cursor location.

## Install

To install - go here and click Install: https://marketplace.visualstudio.com/items?itemName=ScottSauber.blazorsnippets

### For more information

- [GitHub Repository](https://github.com/scottsauber/BlazorSnippets)
