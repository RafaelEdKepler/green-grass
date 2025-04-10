# auto-commit

🌳 Making green your Github stats, powered by [Github Actions](https://github.com/features/actions)

## Make it your own

- Create your own repo with click "**Use this template**" button (⚠️ forked repo will not work)

Or just do in the manual way:

- ✅ Create your own repo
- ✅ Copy file `.github/workflows/autocommit.yml` and `LAST_UPDATED` to your repo
- ✅ You have to configure your repository. Go to: **Settings** -> **Action** -> **General** -> **Workflow permissions** and choose **"Read and write permissions"**
- ✅ Change the `email` and `name` information on file [autocommit.yml, line 29 and 30]
- ✅ Change the scheduling time on file [autocommit.yml, line 10]. You can use [crontab.guru](https://crontab.guru/) if you are not familiar with the cron schedule string. For first time, you can try to run it in every hour with string `1 * * * *` .
- ✅ Consider to support me, at least click the 🌟 button

