<template>
  <div>
    <h1>Github App</h1>
    <GitHubTokenForm></GitHubTokenForm>
    <GithubUser></GithubUser>
    <GithubRepos></GithubRepos>
  </div>
</template>

<script>
import GitHubTokenForm from './components/GitHubTokenForm.vue';
import GithubUser from './components/GithubUser.vue';
import GithubRepos from './components/GithubRepos.vue';

export default {
  name: 'App',
  components: {
    GitHubTokenForm,
    GithubUser,
    GithubRepos,
}
}
</script>

<style>

</style>
