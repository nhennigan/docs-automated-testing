:caption: ~/spread_test_example/tests/example_tutorial/example_tutorial.rst

Demonstrate Spread tests capabilities with a "Hello, world" script
==================================================================

Create a new file ``example_bash_script.sh`` with the following contents:

.. literalinclude:: example_bash_script.sh
    :language: bash

  Make the script executable:

.. literalinclude:: task.yaml
    :language: bash
    :start-after: [docs:make-bash-executable]
    :end-before: [docs:make-bash-executable-end]
    :dedent: 2

Now execute the script:

.. literalinclude:: task.yaml
    :language: bash
    :start-after: [docs:execute-bash-script]
    :end-before: [docs:execute-bash-script-end]
    :dedent: 2

Congratulations! You have created a "Hello, world" script and executed it!
