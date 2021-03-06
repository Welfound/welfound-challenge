# 🎉 The Welfound Challenge

The following challenge shouldn't take more than a few hours to complete for someone brave enough and worthy to embark on
this mission to developing the greatest Community Driven Recruitment platform.

Make sure you read the entire README before starting the challenge.

We have set up almost everything for you to resemble our current stack:

- Prisma (with local SQLite) and the schema you will need for this exercise
- React Query
- Material UI
- Styled Components

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

### ❓ 1. The Questions

To make sure you have pretty good understanding of React and some parts of the toolchain we would like you to answer
the following questions. Please provide your answer in the "arrays" 🤓

```typescript
q[0] =
  'What are some projects that you worked on recently and what were some of the challenges you had to overcome?';
a[0] = `

`;

q[1] = 'What are some uses of refs';
a[1] = `

`;

q[2] = 'What is the difference between a refs and a forwardRefs';
a[2] = `

`;

q[3] = 'What are some benefits of using hooks?';
a[3] = `

`;

q[4] =
  'What is props drilling and why it can become a problem? Can you specify ways to avoid it?';
a[4] = `

`;

q[5] = `How would you make sure that you don't over-fetch data from the server?`;
a[5] = `

`;

q[6] = 'What are the advantages of using TypeScript?';
a[6] = `

`;

q[7] = 'What are TypeScript generics and when are you most likely to use them?';
a[7] = `

`;

q[8] = 'What is babel and why would one use it?';
a[8] = `

`;

q[9] =
  'What is considered a good unit test? What library would you use for unit testing?';
a[9] = `

`;

q[10] = 'What are the advantages of NextJS?';
a[10] = `

`;

q[11] = 'What are the advantages of StyledComponents?';
a[11] = `

`;

q[12] = 'What is GitHub and what are the benefits of Pull Requests?';
a[12] = `

`;

q[13] = 'Can you explain GitHub flow?';
a[13] = `

`;

q[14] = 'What are GitHub Actions? Have you ever used them?';
a[14] = `

`;
```

### 🎯 2 The Technical test:

Just to make sure that you are the right person to embark on our mission we'll make the test a bit (but not very)
challenging

The only set-in-stone requirement is that you have to use TypeScript.

## 🎬 Getting Started

First clone this project on your local machine and install the dependencies

```
git clone git@github.com:Welfound/welfound-challenge.git
cd welfound-challenge
yarn
```

Second, run the development server:

```bash
yarn dev
```

Once you are finished, you have to push your work onto your own **private** GitHub repository.

You will have to add `ovidb` be as a contributor to the repo so that we can look at your work.

We like small and often commits, but it is up to you how you commit.
The end result is what matters the most

### 🧱 The "feature"

```
 ℹ️ Don't worry we don't usually work out of PNG files 😄
 We use Figma for our design files.

 Design is really important to us but we care a lot more about
 solving the underling issues in recruitment the industry.

 We will not be judging or expecting pixel perfect designs (yet😛)
```

- [ ] Create a **Jobs Card** according to the "[design](docs/features/shortlist/card.png)".

  - Make sure to use Material-UI and StyledComponents to create the card.

- [ ] Create a **Jobs Page** under the `/jobs` route
- [ ] On the **Jobs Page**, display the two existing jobs as a list using the card.

  - Fetch the data from the already created `/api/jobs` endpoint using ReactQuery.

  - Use axios if you want together with ReactQuery.

  - Bonus points if you figure out how to use `initialData` received from `getServerSideProps`

  ℹ️ In case you have no data in the response make sure to run `yarn seed`.

#### ⭐️ Bonus point and golden stars

If you decide to do any (or all if you feel brave) the following optional tasks, you will for sure raise your chances but
we do understand time is a luxury item, so, it's definitely not a requirement!

- [ ] Create a unit tests (it doesn't matter what library you're, but we do like [react-testing-library](https://testing-library.com/docs/react-testing-library/intro/))

⚠️ Please note that this technical test is private and not to be shared with anyone.
