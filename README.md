# Initial Interaction Notes Process

In my time I have had many Initial Interaction's whether that be with a person, a business or a product, I always felt that this being documented was missed by many, yet it is something that we do today, even without thinking about it, as they form some of those "mental notes" that we may take.

I've always found these are where most people determine whether they either like or dislike a project, without having spent a decent amount of time with the project.

They are when given to a project team one of the best ways of providing feedback in a way that allows that project team to review and iterate on, particularly if those notes are coming from direct team members or groups of `trusted advisors` like those that have been granted awards like `Microsoft Most Valued Professional MVP` or `AWS Heroes` or `HashiCorp Ambassadors` or `GitHub Stars` to name a few that are out there in the technology communities.


Note - these may be useful for a whole release of a product, or more likely, be used to gain feedback on smaller feature releases.

## What are IIN's

IIN's are a new note type and are of use for detailing any comments about that interation an individual/team may have on a project.
These are to be used, accepted, and requested as a PR from anyone that has an Initial Interaction with the project.

IIN's can either be a shallow set of notes, this may be a simple `all looks good, barring minor comments` or may be used when interacting with a specific part of a project.
IIN's can also be a highly detailed set of notes.

There is no limit to number of IIN's a user can submit, **however** they should always link back to previous IIN's. This enables the user to show the evolution of their understanding, which will help project maintainers and collaborators, in being able to work with that user


## How to Submit an IIN

Projects can decide on whether they want to contain IIN's within their repository or whether they have a dedicated repository where these IIN's and other Project Docs are stored.

If they store them in the repository, they are stored in `./docs/IINs/`
If they store them elsewhere then they should still store them in whichever repo they designate and should be stored in `./docs/IINs/`.

Storing them externally allows for teams to have muiltiple feedback repositories that are collected from different groups during the development processs of the project ensuring that the correct access is respected. 
Storing them either internally with the project, or with a general project docs repository gives the greatest level of transparency.

They should use the [IIN-Template](./InitialInteractionNotes/IIN-Template.md)

## Why should we use IINs

In my many years of interacting with different projects I found that due to us all coming from different backgrounds there is never a baseline of knowledge that is shared by all coming to projects like this.

This makes it difficult to understand just how much of the output of the project that an individual truly understands, and by using IIN's you can see how an individual has progressed in their knowledge of a project, as the project has evolved.

This is useful on so many levels as enables us to find gaps in knowledge and enable us opportunities for future teachable moments, either by those that maintain the project or by the community that are working with the project.

By reviewing IIN's project teams can take actions from those notes, whether it be individual followup or by bringing a bunch of similar actions together all at once.

By having them documented, this helps project teams, as well as those new to projects, understand the development process and velocity in a much more structured way.

This also helps in stopping misunderstandings about the project especially if it is a reasonably mature project.


## Using IIN's for the greatest impact

Utilising IIN's and the feature set of GitHub workflows (Also available in Azure Pipelines) would allow for an individual to provide feedback to a team, and then be notified about reviewing that feedback automagically.

This helps Individual Contributors (IC's) to provide feedback to project teams whilst removing an admistration overhead of remembering to do so by making use of automation to create review issues for either an individual or groups of individuals.

This further aids in making, often invisible work, visible, particularly if it is then added to visible project boards that are either publically visible or privately shared with a select group of individuals/teams.

### Project Goals

This project has a number of goals

- Usable Templates
- Usable workflow defininitions
  - Whether they be github workflows or Azure Pipeline definitions.
  - Potential usable github actions/ Azure Pipeline Tasks
  - Possible Power Automate tasks if used with OneNote's 
- Adopted by
  - Software Development Teams
  - Business Development Teams
  - Consultants
- Supplements the Issues/Discussions/PR's process
- Not just codified like this but also used in existing processes with existing productivity tooling like Power Automate or other process workflow tooling.
- Ability for these to be used as blog posts or to help in building blog posts or other forms of content.
- Greater documentation and sharing of notes.


# Using IIN's

If you are interested in using IIN's then please do the following

- Submit a PR with your IIN of this project into a folder with your username under the `InitialInteractionNotes` path see [my own at](InitialInteractionNotes\kilasuit\2025-03-29-kilasuit-01-IIN.md)
- Add yourself as an Adopter in the ADOPTERS.md file
- Spead the word with your teams and on social media.
- Provide actionable feedback as to where and how to use this as best possible
- When used and feedback from 1 or more IIN's has been actioned in your products pleae make sure to call this out in any changelogs/release notes.
