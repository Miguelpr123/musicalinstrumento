---
layout: page
title: Blog
permalink: /blog/
---

<div class="container-fluid ">
    <div class="row">
        <div class="col-12">
            <div class="container-fluid">
                <div class="row justify-content-around">

                    {%- for posts in site.posts -%}
                        {% include post_card.html %}                       
                    {%- endfor -%}

                </div>
            </div>
        </div>
    </div>
</div>



