Built using JS Mastery tutorial at https://www.youtube.com/watch?v=0fYi8SGA20k&t=7266s

To install dependencies (12:00 in the video):

npm install @react-three/fiber @react-three/drei maath react-parallax-tilt react-vertical-timelime-component @emailjs/browser framer-motion react-router-dom

Which includes the following change from the video:

At 12:00, use react-parallax-tilt instead of react-tilt and remove --legacy-peer-deps from the command.
Also wherever you are using: import Tilt from "react-tilt", replace it with your new library like this: import Tilt from "react-parallax-tilt".

The StarsCanvas component was also modified to solve an issue, for details see
https://github.com/adrianhajdin/project_3D_developer_portfolio/issues/7
