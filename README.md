<p align="center"><img width='300px'src="https://media.tenor.com/8tr_CU6730MAAAAC/web-dev-website-development.gif"/></p>
<h1 align="center">Hi 👋, I'm Harpreet</h1>

<p align="center">📫 How to reach me  <a href="mailto:mallharpreet@hotmail.ca">Email </a></p>


```javascript


const About = () => {
  const getCurrentWorkplace = () => ({
    workplace: {
      company: 'Squared',
      position: 'Full stack developer - Team lead',
      location: 'Toronto'
    }
  });

  const getDailyKnowledge = () => ([
    'React',
    'Next.js',
    'Javascript',
    'TailwindCss',
    'Styled Components',
    'Typescript',
    'Redux',
    'AWS-S3',
    'MongoDb',
    'NodeJs',
    'jest.js',
    'git',

  ]);

  const getFutureGoal = () => 'To contribute to open source.';


  return (
    <div>
      <h1>Current Workplace</h1>
      <p>Company: {workplace.company}</p>
      <p>Position: {workplace.position}</p>
      <p>Location: {workplace.location}</p>

      <h1>Daily Knowledge</h1>
      <ul>
        {getDailyKnowledge().map((knowledge, index) => (
          <li key={index}>{knowledge}</li>
        ))}
      </ul>

      <h1>Future Goal</h1>
      <p>{getFutureGoal()}</p>
    </div>
  );
};

export default About;


```
