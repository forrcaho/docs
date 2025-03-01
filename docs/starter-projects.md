---
title: Starter Projects
description: A collection of starter code and templates for building Battlesnakes!
---

import Link from '@docusaurus/Link'
import CardLink from '@site/src/components/CardLink';

export const officialProjects = [
  {
    name: 'Python',
    href: 'https://github.com/BattlesnakeOfficial/starter-snake-python',
    Svg: require('@site/static/img/icons/python.svg').default
  },
  {
    name: 'Go',
    href: 'https://github.com/BattlesnakeOfficial/starter-snake-go',
    Svg: require('@site/static/img/icons/go.svg').default
  },
  {
    name: 'Rust',
    href: 'https://github.com/BattlesnakeOfficial/starter-snake-rust',
    Svg: require('@site/static/img/icons/rust.svg').default
  },
  {
    name: 'TypeScript',
    href: 'https://github.com/BattlesnakeOfficial/starter-snake-typescript',
    Svg: require('@site/static/img/icons/typescript.svg').default
  },
  {
    name: 'JavaScript',
    href: 'https://github.com/BattlesnakeOfficial/starter-snake-javascript',
    Svg: require('@site/static/img/icons/javascript.svg').default
  }
]

export const OfficialProjects = ({projects}) => (
  <div className="row">
    {projects.map((p) => (
      <div key={p.name} className="col col--4">
        <CardLink to={p.href} bodyStyle={{ display: 'flex', alignItems: 'center', gap: '10px' }}>
          <p.Svg role="img" style={{width: '20px'}} />
          <p>{p.name}</p>
        </CardLink>
      </div>
    ))}
  </div>
)

export const communityProjects = [
  {
    name: 'C\# Starter on Microsoft Azure',
    href: 'https://github.com/neistow/battlesnake-starter-csharp',
    author: 'neistow',
    authorHref: 'https://github.com/neistow'
  },
  {
    name: 'Dart Shelf Starter Project',
    href: 'https://github.com/hotdang-ca/starter-snake-dart-shelf',
    author: 'James Robert Perih',
    authorHref: 'https://github.com/hotdang-ca'
  },
  {
    name: 'F\# Starter Project',
    href: 'https://github.com/olivercoad/battlesnake-starter-fsharp',
    author: 'olivercoad',
    authorHref: 'https://github.com/olivercoad'
  },
  {
    name: 'Haskell Starter with Heroku',
    href: 'https://github.com/ccntrq/starter-snake-haskell',
    author: 'Alexander Pankoff',
    authorHref: 'https://github.com/ccntrq'
  },
  {
    name: 'Java Starter Project',
    href: 'https://github.com/battlesnakeofficial/starter-snake-java',
    author: 'BattlesnakeOfficial',
    authorHref: 'https://github.com/BattlesnakeOfficial'
  },
  {
    name: 'Java Starter Project with JBang and Quarkus',
    href: 'https://github.com/jbangdev/jbang-battlesnake',
    author: 'Max Rydahl Andersen',
    authorHref: 'https://github.com/maxandersen'
  },
  {
    name: 'JavaScript Starter Project with IBM Cloud',
    href: 'https://github.com/IBM/starter-snake-node',
    author: 'Steve Martinelli',
    authorHref: 'https://github.com/stevemar), IBM Cloud'
  },
  {
    name: 'Julia Starter Project',
    href: 'https://github.com/Nettogrof/starter-snake-julia',
    author: 'Nettogrof',
    authorHref: 'https://github.com/Nettogrof'
  },
  {
    name: 'Julia Starter Project',
    href: 'https://github.com/luigiannelli/starter-snake-julia',
    author: 'luigiannelli',
    authorHref: 'https://github.com/luigiannelli'
  },
  {
    name: 'Kotlin Starter Project',
    href: 'https://github.com/770grappenmaker/starter-snake-kotlin',
    author: 'NotEvenJoking',
    authorHref: 'https://github.com/770grappenmaker'
  },
  {
    name: 'Kotlin and Java Battlesnake Quickstart',
    href: 'https://github.com/pambrose/battlesnake-quickstart',
    author: 'Paul Ambrose',
    authorHref: 'https://github.com/pambrose'
  },
    {
    name: 'Mule and DataWeave Battlesnake Quickstart',
    href: 'https://github.com/manikmagar/mule-battlesnake-starter',
    author: 'Manik Magar',
    authorHref: 'https://github.com/manikmagar'
  },
  {
    name: 'PHP Starter Project',
    href: 'https://github.com/Nettogrof/starter-snake-php',
    author: 'Nettogrof',
    authorHref: 'https://github.com/Nettogrof'
  },
  {
    name: 'PowerShell Starter Project with Azure Functions',
    href: 'https://github.com/hestan-net/starter-snake-powershell',
    author: 'Hestan',
    authorHref: 'https://github.com/hestan-net'
  },
  {
    name: 'Node-RED Low-Code Starter Project',
    href: 'https://flows.nodered.org/flow/6cbf34b31e1890bb7a638005bcc4f54b',
    author: 'Sam Machin',
    authorHref: 'https://github.com/sammachin'
  },
  {
    name: 'Reinforcement Learning Battlesnake with AWS Sagemaker',
    href: 'https://github.com/awslabs/sagemaker-battlesnake-ai',
    author: 'Jonathan Chung',
    authorHref: 'https://github.com/jonomon), AWS'
  },
  {
    name: 'Ruby Starter Project',
    href: 'https://github.com/battlesnakeofficial/starter-snake-ruby',
    author: 'BattlesnakeOfficial',
    authorHref: 'https://github.com/BattlesnakeOfficial'
  },
  {
    name: 'Rust Starter Project',
    href: 'https://github.com/mcraealex/rustysnake',
    author: 'McRaeAlex',
    authorHref: 'https://github.com/McRaeAlex'
  },
  {
    name: 'Scala Starter Project with Heroku',
    href: 'https://github.com/horrox/battlesnake-starter-scala',
    author: 'horrox',
    authorHref: 'https://github.com/horrox'
  },
  {
    name: 'TypeScript Starter Project',
    href: 'https://github.com/kgorgi/starter-snake-node-ts',
    author: 'Kian Gorgichuk',
    authorHref: 'https://github.com/kgorgi'
  },
  {
    name: 'TypeScript and Deno Starter Project',
    href: 'https://github.com/tyrelh/starter-snake-typescript-deno',
    author: 'Tyrel Hiebert',
    authorHref: 'https://github.com/tyrelh'
  },
  {
    name: 'Elixir Snake with Fly.io',
    href: 'https://github.com/sockbot/elixir-starter-battlesnake',
    author: 'Andy Chan',
    authorHref: 'https://github.com/sockbot'
  },
  {
    name: 'Swift Starter Project',
    href: 'https://github.com/maartene/BattlesnakeSwiftStarter',
    author: 'Maarten Engels',
    authorHref: 'https://github.com/maartene'
  }
]

export const CommunityProjects = ({projects}) => (
  <div className="row">
    {projects.map((p) => (
      <div className="col col--4">
        <CardLink to={p.href} style={{height: '80%'}}>
          <p className="margin-bottom--none">{p.name}</p>
          <p style={{color: 'var(--ifm-color-content)', fontSize: '.8rem'}}>by {p.author}</p>
        </CardLink>
      </div>
    ))}
  </div>
)

These projects and templates are great starting points for building your Battlesnake. They're available for many different programming languages and platforms &mdash; some maintained by Battlesnake core team members and others contributed by the Battlesnake community.

## Starter Project Templates

These projects are built and maintained by Battlesnake core team members. We do our best to keep them functional and up-to-date with the latest game features. If something doesn't work as you'd expect or needs updating, [please let us know](https://play.battlesnake.com/feedback) so we can make changes :)

If you're building a Battlesnake for the first time these are great starting points.

<OfficialProjects projects={officialProjects} />

:::tip
**These projects are GitHub Templates**, and we recommended clicking the green _"Use this template"_ button to bring a clean copy of the starter code into your own GitHub account. You are also welcome to [fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) one of these repos instead, but please do not submit Pull Requests back to the template repos.
:::

## Community Projects

The Battlesnake community is all about collaboration and shared learning. Sometimes players will build their own starter projects featuring new combinations of languages and platforms and share them back to the community to help new players get started!

<CommunityProjects projects={communityProjects} />

:::info
**These projects are maintained independently by their developers.** See project guidelines for each project if you're interested in getting involved or have any questions or concerns.
:::

## Contributing

**Want to submit your own projects to this list? Wonderful!** Community starter projects must match the following criteria to be listed:

* Contain just enough code to run a simple Battlesnake and nothing more
* Be well documented and easy to understand
* Ideally have a minimal project structure

If your project fits, feel free to submit a [pull request](https://github.com/BattlesnakeOfficial/docs) or [start a discussion thread](https://play.battlesnake.com/feedback) and we'll take a look!
