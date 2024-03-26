<template>
  <main>
    <div>
      {{
        new Date().toLocaleDateString('en-US', {
          weekday: 'long',
          year: 'numeric',
          month: 'long',
          day: 'numeric',
          hour: 'numeric',
          minute: 'numeric',
          second: 'numeric',
          timeZone: 'Asia/Jakarta'
        })
      }}
      <p>Asia/Jakarta</p>
    </div>
  </main>
</template>
