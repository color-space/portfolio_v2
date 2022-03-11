<template>
    <div class="flex flex-col w-full border-opacity-50">
        <div id="bio" class="flex place-content-between">
            <div class="avatar">
                <div class="h-24 rounded-xl">
                    <img src="/avatar.jpg" />
                </div>
            </div>
            <div id="description" class="w-96">
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Pellentesque euismod, urna eu tincidunt consectetur,
                    nisi nisl aliquam nunc, eget consectetur nunc nisl eu
                    ligula.
                </p>
            </div>
        </div>

        <div class="divider whitespace-nowrap -mx-10">Current Skills</div>
        <div
            id="current_skills"
            class="grid gap-5 grid-flow-col auto-cols-max auto-rows-max hover:auto-rows-min min-h-20 px-5 py-5 card bg-base-300 rounded-box place-items-center"
        >
            <div class="card w-64 bg-base-100 shadow-xl">
                <figure class="bg-gradient-to-tr from-yellow-500 to-yellow-300 text-primary">
                    <simple-icons:javascript class="h-32 w-32 p-5 m-2"/>
                </figure>
                <progress class="progress w-full h-4 color-red" value="70" max="100"></progress>
                <div class="card-body">
                    <h2 class="card-title">Javascript</h2>
                    <p>If a dog chews shoes whose shoes does he choose?</p>
                </div>
            </div>

            <div class="card w-64 bg-base-100 shadow-xl">
                <figure>
                    <img src="https://api.lorem.space/image/shoes?w=400&h=225" alt="Shoes" />
                </figure>
                <progress class="progress w-full h-4 color-red" value="70" max="100"></progress>
                <div class="card-body">                    
                    <h2 class="card-title">Vue</h2>
                    <p>If a dog chews shoes whose shoes does he choose?</p>
                </div>
                
            </div>
        </div>
        <div class="divider whitespace-nowrap -mx-10">Future Interests</div>
        <div id="future_skills" class="grid h-20 card bg-base-300 rounded-box place-items-center"></div>
    </div>
</template>