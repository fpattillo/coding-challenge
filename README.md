# Live Coding Challenge

Welcome to this fast Datascope live coding challenge. 

Here we have a Fantasy Dragon Ball team builder app. The objective of this app is to allow users to create the best 10-member DBZ team.

- [ ] There are some typescript bad practices in components CharacterCard and TeamCard please fix them.
- [ ] Make the necessary changes to allow the app to add AND remove members to the team but you can't change anything in the `TeamCard.tsx` component. Team shouldn't have more than 10 members and you can't add the same character twice. The "Add to Team" button should only be displayed if the character is not on the team. Otherwise, the "Remove from Team" button should be displayed.
- [ ] Currently the list of characters come from a static file. Now they should be fetched from [Dragon Ball API](https://web.dragonball-api.com/documentation) specifically from `https://dragonball-api.com/api/characters`endpoint. Please fetch the first 30. You can use fetch API or axios.
- [ ] Combined Ki is not changing when you add team members please fix it.
- [ ] Combined Ki is not being properly calculated please fix it.