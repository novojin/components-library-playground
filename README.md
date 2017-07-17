First, if not done, from the root of our component library, run npm link.
Now we’ll tell our playground app that we want to use that symlinked library. From the root of the playground app run: npm link components-library

example: import { Button } from 'components-library';
run npm start
