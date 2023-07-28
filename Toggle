import React, { Component } from 'react';

class ToggleColor extends Component {
  state = {
    isToggled: false,
    colors: ['red', 'green', 'blue'],
  };

  handleToggle = () => {
    this.setState({
      isToggled: !this.state.isToggled,
    });
  };

  render() {
    const currentColor = this.state.isToggled
      ? this.state.colors[0]
      : this.state.colors[2];

    return (
      <div style={{ backgroundColor: currentColor }}>
        <button onClick={this.handleToggle}>Toggle Color</button>
      </div>
    );
  }
}

export default ToggleColor;
