# function-drag
  function drag() external {
        if (hasClaimed[msg.sender]) {
            revert TokensClaimed();
          }
