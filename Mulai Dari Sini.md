# Reporting Dashboard

![alt text](/img/dashboard.png)

---

## Ini adalah contoh Dashboard yang dibangun menggunakan [SvelteKit](https://kit.svelte.dev/) sebagai Frontend dan  [Supabase](https://supabase.com/)  sebagai Backend

<h3>
<span style="color:red">
------- 
</h3>
</span>

## Demo Dashboard

Untuk melihat dashboard berdasarkan akses role silahkan [klik disini](https://sveltekit-supabase-dashboard.vercel.app/).

## Fitur Yang Dimiliki

- User Interface dibuat dengan warna Supabase
- Dashboard bisa dipakai oleh banyak organisasi dengan akun ID masing - masing.
- Bisa memiliki beberapa tingkatan role akses di dalam sebuah organization.
- Bisa menambahkan dan menghapus pengguna dari dalam Dashboard.
- Tampilan Table dan Chart 
- Demo mode (show hints and disable database updates)

## Teknologi Yang Dipakai

- [Svelte](https://svelte.dev/) and [SvelteKit](https://kit.svelte.dev/) as application framework
- [Supabase](https://supabase.com/) as database and backend
- [TailwindCSS](https://tailwindcss.com/) as CSS framework
- [DaisyUI](https://daisyui.com/) as Tailwind CSS component library
- [Supabase Auth Helpers](https://github.com/supabase/auth-helpers) as Auth utilities for working with Supabase
- [Supabase custom claims](https://github.com/supabase-community/supabase-custom-claims) for multi organization and role based access
- [Charts.js](https://www.chartjs.org/) and [svelte-chartjs](https://www.npmjs.com/package/svelte-chartjs) for charts
- [Feather Icons](https://feathericons.com/) and [svelte-feather-icons](https://www.npmjs.com/package/svelte-feather-icons) for icons
- [svelte-loading-spinners](https://www.npmjs.com/package/svelte-loading-spinners) for loading spinners
- [Vercel](https://vercel.com/) as deployment platform

## Apa Yang Harus Dilakukan?

- Coba tambahkan beberapa dokumentasi code sehingga team lain bisa memahami apa fungsi yang tujuan dari sebuah code.
- Ada beberapa Typescript yang bermasalah.
- Tambahkan Data dan Chart Versi kamu.
- Hubungkan Frontend dengan Supabase
	- [Documentation](https://supabase.com/docs/guides/getting-started/quickstarts/sveltekit)
- Improve mobile version

## Cara Memulai

### Bikin Akun Supabase

1. Silahkan buat Proyek baru di [supabase.com](https://supabase.com/)  
2. Go to Settings API to check your project URL and API keys.

### Clone Repo Ini

```bash
git clone https://github.com/christmantoro/sveltekit-supabase-chartjs.git
cd sveltekit-supabase-chartjs
```

### Setup environment variables

Create a new `.env` file

```bash
cp .env.example .env
```

Edit your `.env` file to match your project URL and API keys

```bash
# SUPABASE
PUBLIC_SUPABASE_URL="YOUR PROJECT URL"
PUBLIC_SUPABASE_ANON_KEY="YOUR PROJECT ANON KEY"
PRIVATE_SUPABASE_SERVICE_KEY="YOUR PROJECT SERVICE KEY"
```

### Initialize database

Execute `sql/init_databse.sql` and `sql/init_demo_data.sql` in Supabase SQL Editor.

### Install & run

```bash
npm install
```

To start in development mode:

```bash
npm run dev
```

To build and start in production mode:

```bash
npm run build
npm run preview
```

### Deploy

To deploy to Vercel please follow instructions [here](https://vercel.com/guides/deploying-svelte-with-vercel).

## Development

Find more development details [here](https://github.com/xulioc/sveltekit-supabase-dashboard/blob/main/README_DEV.md).

## Contribute

Feel free to contribute. Issues and Pull Requests are welcome.

## License

[MIT](https://github.com/xulioc/sveltekit-supabase-dashboard/blob/main/LICENSE)
