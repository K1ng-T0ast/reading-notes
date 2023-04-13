# React and Forms

## Forms

1. What is a ‘Controlled Component’?

    Form elements maintain their own state and update based on input. State can only be changed by the setState method of mutable components. Controlled components can combine both and control both the rendered form and mutated state within the component itself.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

    Depends on the use case. Storing user responses as soon as entered could provide imemdiate feedback to the user like error messages or form validation, save user responses automatically. Storing user responses when a form is submitted could make forms more secure by limiting unautorized access, could possibly improve app performance because you would be reducing the number of state changes.

3. How do we target what the user is entering if we have an event handler on an input field?

    **event.target.value** (example code block below from https://legacy.reactjs.org/docs/forms.html)

    class NameForm extends React.Component {
    constructor(props) {
        super(props);
        this.state = {value: ''};

        this.handleChange = this.handleChange.bind(this);
        this.handleSubmit = this.handleSubmit.bind(this);
    }

    handleChange(event) {
        this.setState({value: event.target.value});
    }

    handleSubmit(event) {
        alert('A name was submitted: ' + this.state.value);
        event.preventDefault();
    }

    render() {
        return (
        <form onSubmit={this.handleSubmit}>
            <label>
            Name:
            <input type="text" value={this.state.value} onChange={this.handleChange} />
            </label>
            <input type="submit" value="Submit" />
        </form>
        );
    }
    }


## Conditional Ternary Operator

1. Why would we use a ternary operator?

    If we wasnt to achive if statements with less code, and if we want to check conditions of true, false, or coerce a boolean value.

    - The condition is what you’re actually testing. The result of your condition should be true or false or at least coerce to either boolean value.
    - A ? separates our conditional from our true value. Anything between the ? and the : is what is executed if the condition evaluates to true.
    - Finally a : colon. If your condition evaluates to false, any code after the colon is executed.

    (Source from https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

2. Rewrite the following statement using a ternary statement:

    if(x===y){
    console.log(true);
    } else {
    console.log(false);
    }

    console.log(x === y ? true : false);

## Things I want to know more about

**How we can mutate forms in real time based on user input**